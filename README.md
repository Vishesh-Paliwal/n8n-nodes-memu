# n8n-nodes-memu

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This is an n8n community node package that integrates [MemU's](https://memu.so) agentic memory capabilities into n8n workflows. MemU is an agentic memory framework that processes multimodal inputs (conversations, documents, images, videos, audio) into structured, retrievable memory for your AI agents.

## Table of Contents

- [Installation](#installation)
- [Nodes](#nodes)
- [Credentials](#credentials)
- [Configuration Examples](#configuration-examples)
- [Workflow Integration Patterns](#workflow-integration-patterns)
- [Resources](#resources)
- [License](#license)

## Installation

Since this package is built for n8n, you can install it for local development or testing directly from GitHub.

### 1. Install n8n and the MemU node package
Use `pnpm` (or `npm`) to install n8n and this package into your local project:

```bash
pnpm add n8n
pnpm add github:Vishesh-Paliwal/n8n-nodes-memu
```

### 2. Configure n8n to load the custom node
To run n8n and make it recognize the MemU nodes, you need to set the `N8N_CUSTOM_EXTENSIONS` environment variable. 

Add a start script to your `package.json`:

```json
"scripts": {
  "start": "N8N_CUSTOM_EXTENSIONS=./node_modules/n8n-nodes-memu npx n8n start"
}
```

Then run:
```bash
pnpm start
```

## Nodes

This package provides nodes to bridge the gap between your data and AI memory:

### 🧠 MemU Memorize
The core node for building long-term memory. It points at a resource (URL or local path) and extracts "Memory Items" (Knowledge, Profile, Behavior, etc.) automatically.

*   **Modality**: Supports `conversation`, `document`, `image`, `video`, and `audio`.
*   **User Scoping**: Crucial for multi-tenant agents. Attach a `user_id` so the memory remains private to that user.

### 🔍 MemU Retrieve
The bridge for AI responses. It queries the stored memory to find relevant context.

*   **RAG Method**: Fast vector-based similarity search.
*   **LLM Method**: Deep semantic reasoning to find relevant context that simple search might miss.

### 📋 MemU List Categories
Returns a list of all categories the agent has created. This is useful for dynamic routing or building dashboards to show what the agent "knows".

## Credentials

To use these nodes, you need a **MemU Cloud API** credential.

1.  **Base URL**: Use `https://api.memu.so` (default).
2.  **API Key**: Your secret key from the MemU dashboard.


## Workflow Integration Patterns

### Auto-Updating Knowledge Base
Connect a **Google Drive Trigger** to a **MemU Memorize** node. Every time you drop a new file in your drive, your n8n agent automatically "reads" it and updates its knowledge.

### Persistent Chat Experience
1.  **Webhook** receives a chat message.
2.  **MemU Retrieve** fetches what the user said in previous conversations.
3.  **AI Node** generates a personalized response using that context.
4.  **MemU Memorize** (Modality: Conversation) stores the new interaction so it's never forgotten.

## Resources

- [MemU Official Website](https://memu.so)
- [n8n Community Nodes Documentation](https://docs.n8n.io/integrations/community-nodes/)
- [Report Issues](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues)

## License

[MIT](LICENSE) © MemU Team
