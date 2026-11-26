# GenAI Codebase Intelligence

**An AI-powered platform for understanding, analyzing, and exploring GitHub repositories using Generative AI and Retrieval-Augmented Generation (RAG).**

Developed by **Abhishek Vishwakarma**

---

## Overview

GenAI Codebase Intelligence is a project designed to help developers understand large and complex codebases through natural language questions.

Instead of manually navigating multiple files and understanding their relationships, developers can connect a GitHub repository and ask questions about its architecture, authentication, APIs, database interactions, and application workflows.

The platform aims to use Retrieval-Augmented Generation (RAG) to retrieve relevant code snippets and provide context-aware explanations using Large Language Models (LLMs).

## Key Objectives

- Analyze GitHub repositories and their source code.
- Understand project architecture and component relationships.
- Explain authentication and authorization workflows.
- Explore API endpoints and their implementation.
- Understand database interactions and application logic.
- Answer codebase-related questions using natural language.
- Provide relevant source file references with AI-generated explanations.

## Project Structure

```text
genai-codebase-intelligence/
│
├── backend/              # Backend application
│
├── frontend/             # Frontend application
│
└── README.md             # Project documentation
```

## Technology Stack

### Backend
- Java
- Spring Boot
- REST APIs

### Frontend
- Next.js
- React
- JavaScript

### AI and Generative AI
- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)
- Text Embeddings
- Vector Search
- Vector Database

*Specific AI providers and vector database technologies will be documented as they are integrated.*

## How It Works

The planned application workflow consists of the following stages:

1. **Repository Integration:** Connect a GitHub repository to the platform.
2. **Code Ingestion:** Retrieve and extract relevant source code files.
3. **Code Processing:** Process the source code into meaningful chunks.
4. **Embedding Generation:** Convert code chunks into numerical vector representations.
5. **Vector Storage:** Store embeddings and associated metadata for efficient retrieval.
6. **Context Retrieval:** Retrieve relevant code snippets based on the user's question.
7. **AI Response Generation:** Provide the retrieved context to an LLM to generate meaningful explanations.

## Example Use Cases

Developers will be able to ask questions such as:

- How does authentication work in this project?
- Explain the complete login and registration flow.
- Where is JWT generated and validated?
- How do different backend components communicate?
- Which APIs are available in this repository?
- How does the application interact with its database?
- Explain the overall architecture of this project.

## Getting Started

### Prerequisites

- Java Development Kit (JDK)
- Node.js and npm
- Git
- Maven (if not using the Maven Wrapper)

### Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/genai-codebase-intelligence.git

cd genai-codebase-intelligence
```

### Backend Setup

```bash
cd backend
```

Follow the backend-specific setup instructions and configure the required environment variables before running the application.

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

The frontend development server typically runs at:

```text
http://localhost:3000
```

*Backend configuration, environment variables, and AI service setup will be documented as the implementation progresses.*

## Development Status

**Status:** In Development

This project is being developed incrementally, with a focus on building a reliable codebase ingestion pipeline, semantic retrieval system, and AI-powered code understanding experience.

## Author

**Abhishek Vishwakarma**

- GitHub: [@rekandlal](https://github.com/rekandlal)
- LinkedIn: [abhish001](https://www.linkedin.com/in/abhish001/)

---

*Built with a focus on simplifying codebase understanding through Generative AI.*
