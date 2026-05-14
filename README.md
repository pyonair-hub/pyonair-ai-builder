# Pyonair AI Builder

**Your AI Team. Trained on You.**

---

Visual AI agent and workflow builder. Drag-and-drop LLM applications, RAG pipelines, and chatbots. Part of the [Pyonair AI Team](https://pyonair.com) platform.

## What is Pyonair AI Builder?

Pyonair AI Builder is a visual drag-and-drop tool for building AI agents, workflows, and chatbots -- no coding required. Connect large language models, vector databases, tools, and memory systems into powerful AI applications.

### Key Features

- **Visual Agent Builder** -- Drag-and-drop interface for creating AI agents and multi-agent systems
- **RAG Pipelines** -- Build retrieval-augmented generation flows with your own documents
- **Chatbot Builder** -- Deploy conversational AI trained on your business data
- **LLM Orchestration** -- Connect OpenAI, Anthropic, Google, and 100+ model providers
- **Tool Integration** -- APIs, databases, web scraping, code execution, and more
- **Memory & Context** -- Long-term memory, conversation history, and context management
- **API & Embedding** -- Expose any flow as an API endpoint or embed as a chat widget

## Brand

| Element | Value |
|---------|-------|
| Primary Color (Red) | `#E63946` |
| Secondary Color (Navy) | `#0F172A` |
| Font | Inter |

## Tech Stack

- **Runtime**: Node.js
- **Frontend**: React
- **Language**: TypeScript
- **Package Manager**: pnpm
- **Build System**: Turborepo

## Quick Start

```bash
# Install dependencies
pnpm install

# Build all packages
pnpm build

# Start the application
pnpm start
```

Visit `http://localhost:3000` after starting.

## Project Structure

```
packages/
  server/       -- Backend API server (Express)
  ui/           -- Frontend React application
  components/   -- LLM nodes, tools, and integrations
```

## Environment Variables

Copy `.env.example` to `.env` and configure:

```bash
# Database (SQLite by default, supports Postgres/MySQL)
DATABASE_TYPE=sqlite

# API keys for LLM providers
OPENAI_API_KEY=
ANTHROPIC_API_KEY=

# Authentication (optional)
FLOWISE_USERNAME=
FLOWISE_PASSWORD=
```

## License

Apache 2.0 -- see [LICENSE.md](LICENSE.md)

Built on [Flowise](https://github.com/FlowiseAI/Flowise) (Apache 2.0 License).

## Links

- [Pyonair](https://pyonair.com) -- AI Team platform
- [Flowise](https://github.com/FlowiseAI/Flowise) -- Original open-source project
