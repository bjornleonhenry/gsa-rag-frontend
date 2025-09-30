# RAG Frontend Application

A modern React/Next.js application implementing Retrieval-Augmented Generation (RAG) with LangChain, Pinecone vector database, and OpenAI GPT integration.

## Technologies Used

- Next.js - React framework for production
- LangChain.js - Framework for LLM applications
- Pinecone - Vector database for similarity search
- OpenAI GPT - Large language model integration

## Getting Started

### Prerequisites

Before running this application, you'll need:

1. OpenAI API key from [platform.openai.com](https://platform.openai.com/)
2. Pinecone API key and environment from [app.pinecone.io](https://app.pinecone.io/)

### Installation and Setup

1. Clone the repository:
```bash
git clone <repository-url>
cd gsa-rag-frontend
```

2. Install dependencies:
```bash
npm install
# or
pnpm install
# or
yarn install
```

3. Set up environment variables:
```bash
cp .env.example .env.local
# Edit .env.local with your OpenAI and Pinecone credentials
```

4. (Optional) Add your own documents to the `/documents` folder for custom knowledge base

5. Start the development server:
```bash
npm run dev
# or
pnpm run dev
# or
yarn dev
```

The application will be available at `http://localhost:3000`.
