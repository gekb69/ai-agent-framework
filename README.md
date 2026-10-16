# AI Agent Framework

Modular AI agent framework with tool calling, memory, and safe execution.

## Features

- ReAct-style loop with tool integration
- Built-in tools: calculator, sandboxed file I/O, allowlisted command execution, web search (mock)
- OpenAI GPT-4 Turbo with retries and error handling
- Conversation memory with automatic trimming
- Security: no unsanitized eval, path traversal protection, command allowlist
- Unit tests with Jest

## Installation

```bash
git clone https://github.com/gekb69/ai-agent-framework.git
cd ai-agent-framework
npm install
cp .env.example .env
# Edit .env and add your OPENAI_API_KEY
npm run build
npm start
```
