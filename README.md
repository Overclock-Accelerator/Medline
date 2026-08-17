# Medline

A hosted surgical-supplies CRM plus an AI agent equipped with 12 custom tools (search, create,
update, delete, and report on CRM data) — a demo of a tool-powered chat interface built on
Next.js, backed by Supabase.

## Demos

- `/crm` — Surgical Supplies CRM with a credentialized API.
- `/agent` — Chat interface where the LLM calls CRM tools to act on data.

## Local development

```bash
cp .env.example .env.local   # fill in real values
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Environment variables

See `.env.example` for the full list (LLM provider keys, Supabase keys, CRM shared secret).
In production these are set as encrypted Vercel Environment Variables, not committed to git.

## Deploy

Deployed on [Vercel](https://vercel.com).
