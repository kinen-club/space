---
date: 2025-11-30T00:00:00Z
artifact_type: session_init
tags:
  - space/work
  - status/example
summary: "Example session showing the structure and flow"
---

# Example Session: Architecture Design

**Initiated**: Via email to your Kinen inbox
**Status**: 🟢 Example

---

## Initial Request

"I need to design a user authentication system for our mobile app. It should support email/password and OAuth (Google, Apple). We expect 100K users in the first year."

---

## What Happens Next

The AI agent will:
1. Create this session branch
2. Ask clarifying questions in Round 01
3. Generate artifacts based on your responses
4. Email you updates at each step

All work is saved in this Git branch: `session/issue-N`

---

## Session Structure

```
example-session/
  init.md           # This file (initial request)
  rounds/
    01-questions.md # AI's clarifying questions
    01-answers.md   # Your responses
    02-proposal.md  # AI's design proposal
    02-feedback.md  # Your feedback
  artifacts/
    auth-spec.md    # Living document
    architecture.md # System design
```

---

## Tips

- Reply to emails to continue the conversation
- All changes are tracked in Git
- Session ends when you merge the branch to main
- Use `spaces/work/` for professional projects
- Use `spaces/personal/` for personal work
