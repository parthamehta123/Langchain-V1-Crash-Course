# LangChain v1 crash course (practice)

Practice notebooks for LangChain v1 and an LLM gateway built with LiteLLM. Local edits update retired model IDs and API wiring so the gateway tutorial runs against current Groq, Gemini, and Anthropic models.

## Setup

```bash
cp .env.example .env   # or create a .env with your keys
# OPENAI_API_KEY=...
# GROQ_API_KEY=...
# GOOGLE_API_KEY=...   # or GEMINI_API_KEY
# ANTHROPIC_API_KEY=...
```

`.env` is gitignored. Do not commit API keys.
