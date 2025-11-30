# My Kinen Space

Your workspace for AI-powered thinking sessions.

---

## 🚀 Step 1: Enable Kinen

**[Click here to install the Kinen App →](https://github.com/apps/kinen-club)**

This connects your repo to Kinen and sets up your email inbox.

---

## 🔑 Step 2: Add API Key

Add **one** API key to your repo secrets (Settings → Secrets → Actions):

| Provider | Secret Name | Get Key |
|----------|-------------|---------|
| **OpenRouter** (recommended) | `OPENROUTER_API_KEY` | [Free tier available](https://openrouter.ai/keys) |
| Gemini | `GEMINI_API_KEY` | [Free tier](https://aistudio.google.com/apikey) |
| OpenAI | `OPENAI_API_KEY` | [Paid](https://platform.openai.com/api-keys) |
| Anthropic | `ANTHROPIC_API_KEY` | [Paid](https://console.anthropic.com/) |

---

## 📧 Step 3: Start a Session

After setup, email your inbox to start:

```
To: my-project@YOUR-USERNAME.kinen.space
Subject: Build a todo app with React
```

You'll receive AI responses via email. Reply to continue the conversation!

---

## How It Works

```
You send email → AI creates GitHub issue → AI asks questions
       ↑                                          ↓
  Reply to continue ← You get email ← AI generates code
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
