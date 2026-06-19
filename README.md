# Srakshin's OpenCode Setup & Agents Workflow

This project is an AI-powered project planner built on the **opencode** framework. It uses an intelligent agent to take app ideas and turn them into structured, beginner-friendly project plans — complete with data models, features, and tech recommendations.

Built with **Next.js (App Router)** and powered by OpenRouter AI models (Claude, GPT, etc.), the planner acts as a coding companion that helps you scope and plan your next project before writing a single line of code.

## Features

- **AI Project Planner** — Describe your idea and get a structured plan with data models, pages, and feature breakdowns
- **Agent Workflow** — OpenCode agents orchestrate research, planning, and code generation tasks
- **Beginner-Friendly** — Plans avoid unnecessary complexity (no auth, DB, or payments unless essential)
- **OpenRouter Integration** — Switch between multiple AI models via the `OPENROUTER_MODEL` env variable

## Getting Started

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser.

## Env Variables

Create a `.env.local` file:

```env
OPENROUTER_API_KEY=your_key_here
OPENROUTER_MODEL=anthropic/claude-sonnet-4.6
```

---

Made by **Srakshin**
