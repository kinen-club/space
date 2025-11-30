---
date: 2025-11-30T00:00:00Z
artifact_type: round_exploration
tags:
  - space/work
  - status/example
summary: "Example of AI clarifying questions"
---

# Round 01: Understanding Requirements

Based on your request to design an authentication system, I have some clarifying questions:

## Current State

1. **Existing Infrastructure**: Do you have an existing backend? If so, what technologies?
2. **User Data**: Where will user data be stored? Any compliance requirements (GDPR, HIPAA)?

## Technical Constraints

3. **Mobile Platforms**: iOS only, Android only, or both?
4. **Session Management**: What session duration expectations? (e.g., 30 days, forever unless logout)
5. **Security Requirements**: Any specific security standards or certifications needed?

## OAuth Integration

6. **OAuth Providers**: Confirmed Google and Apple. Any others planned?
7. **Account Linking**: Can users link multiple OAuth providers to one account?

## Scale & Performance

8. **100K users first year**: What's the expected growth after that?
9. **Peak Load**: Any expected traffic spikes (launch day, campaigns)?

---

## How to Respond

Simply reply to the email with your answers. Number them for clarity:

```
1. We use Node.js + PostgreSQL...
2. PostgreSQL on AWS RDS, yes we need GDPR compliance...
(etc)
```

The AI will use your responses to generate a detailed proposal in Round 02.
