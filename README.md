# Kinen Space

Your personal workspace for AI-powered sessions.

## Quick Start

1. **Use this template** to create your repo
2. **Add an API key** to repo secrets (see below)
3. **Push a commit** to trigger setup
4. **Check your email** for your inbox address
5. **Start a session** by emailing your inbox

That's it!

---

## LLM Provider Setup

Add **one** of these secrets to your repo (Settings → Secrets → Actions):

| Provider | Secret Name | Free Tier? | Notes |
|----------|-------------|------------|-------|
| **Google Gemini** | `GEMINI_API_KEY` | ✅ Yes | [Get free key](https://aistudio.google.com/apikey) |
| OpenAI | `OPENAI_API_KEY` | ❌ No | Pay-per-use |
| Anthropic | `ANTHROPIC_API_KEY` | ❌ No | Pay-per-use |

### Recommended: Gemini (Free)

1. Go to: https://aistudio.google.com/apikey
2. Sign in with Google
3. Click **Create API Key**
4. Copy the key
5. Add to repo secrets as `GEMINI_API_KEY`

---

## What is Kinen?

Kinen is a round-based methodology for working through complex problems with AI. It works via email:

- **Email your inbox** to start a session
- **AI asks questions** in return
- **You answer** by replying
- **Repeat** until you're done

All your work is saved to this repo as structured files.

---

## The Kinen Methodology

The AI follows a structured thinking process:

1. **Round-based exploration** - Deep questions, not shallow chat
2. **Challenge assumptions** - The AI pushes back constructively
3. **Provide options** - Multiple approaches with tradeoffs
4. **Build incrementally** - Each round builds on the previous

### Base + Custom

The methodology has two layers:

1. **Base Methodology** (from [kinen.club/methodology](https://kinen.club/methodology))
   - Core protocol, quality standards, thinking partner role
   - Automatically fetched for every session

2. **Your Custom Instructions** (`.kinen/custom-instructions.md`)
   - Your project context, coding standards, preferences
   - You edit this file to customize the AI

Edit `.kinen/custom-instructions.md` to:
- Add your project/domain context
- Define your preferred coding standards
- Set communication preferences
- Include examples the AI should follow

---

## Session Types

Kinen works for any iterative thinking process:
- Technical architecture reviews
- Writing projects (articles, books, scripts)
- Strategic planning
- Research and analysis
- Design reviews
- Code implementation

---

## How It Works

```
You Email
    ↓
AI Creates GitHub Issue
    ↓
AI Fetches Methodology + Your Custom Instructions
    ↓
AI Processes with Kinen Methodology
    ↓
AI Generates Code/Artifacts
    ↓
You Get Email with Results
    ↓
Reply to Continue
```

---

## File Structure

After a few sessions, your repo will look like:

```
.kinen/
  custom-instructions.md   # Your custom additions
  config.yml               # Session settings

spaces/
  work/
    sessions/
      20251130-01-architecture-review/
        session.md
        artifacts/
          architecture-diagram.png
          tech-spec.md
  personal/
    sessions/
      20251130-01-novel-outline/
        ...
```

---

## Privacy

- Your repo is **yours** (private or public, your choice)
- Your email inbox is **unique to you**
- No central database - everything lives in Git
- API keys are stored as GitHub secrets (encrypted)

---

## Troubleshooting

### "No LLM API key configured"
Add `GEMINI_API_KEY`, `OPENAI_API_KEY`, or `ANTHROPIC_API_KEY` to repo secrets.

### Workflow not running
- Check Actions tab for errors
- Ensure Actions are enabled (Settings → Actions → General)

### No email received
- Check spam folder
- Verify you pushed a commit after creating the repo

---

## Support

- Questions? https://github.com/kinen-club/space/issues
- Documentation: https://github.com/kinen-club/club

---

## License

MIT
