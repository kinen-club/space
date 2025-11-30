# My Kinen Space

Your workspace for AI-powered thinking sessions.

## Quick Start

1. Add an API key to repo secrets (see below)
2. Email your inbox to start a session
3. Reply to continue the conversation

## Setup

Add **one** API key to your repo secrets (Settings → Secrets → Actions):

| Provider | Secret Name | Free? |
|----------|-------------|-------|
| **Gemini** | `GEMINI_API_KEY` | ✅ [Get free key](https://aistudio.google.com/apikey) |
| OpenAI | `OPENAI_API_KEY` | Paid |
| Anthropic | `ANTHROPIC_API_KEY` | Paid |

## How It Works

```
You email your inbox
    ↓
AI creates a session (GitHub issue)
    ↓
AI asks questions, generates code
    ↓
You get email with results
    ↓
Reply to continue
```

## File Structure

```
sessions/
  my-project-auth/
    init.md           # Session goals
    rounds/
      01-questions.md # AI questions + your answers
      02-design.md
    artifacts/
      auth-spec.md    # Generated documents

.kinen/
  config.yml              # Settings
  custom-instructions.md  # Your customizations
```

## Customizing the AI

Edit `.kinen/custom-instructions.md` to add:
- Your project context
- Coding standards
- Communication preferences

## Multiple Spaces

Want separate spaces for work and personal projects?
Create multiple repos from this template.

## License

MIT
