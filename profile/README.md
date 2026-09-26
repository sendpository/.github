# Sendpository

Transactional email API for developers.
Send your first application email with one HTTP request.

```bash
curl -X POST https://api.sendpository.com/v1/emails \
  -H "Authorization: Bearer $SENDPOSITORY_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"from":"Acme <hello@mail.yourdomain.com>","to":["you@example.com"],"subject":"Hello","html":"<p>It works.</p>"}'
```

Building with an AI coding agent? `npx sendpository agents` teaches Claude
Code, Codex, Cursor and Copilot how Sendpository works - then ask it to add
email, or to move you off another provider. [How it works](https://sendpository.com/agents)

| Repository | What it is |
|---|---|
| [sendpository-node](https://github.com/sendpository/sendpository-node) | Node.js and TypeScript SDK - `npm install sendpository` |
| [sendpository-examples](https://github.com/sendpository/sendpository-examples) | Runnable examples: Next.js, Node.js, Python, PHP, Go |

[Docs](https://sendpository.com/docs) · [API reference](https://sendpository.com/docs/api-reference/emails) · [Guides](https://sendpository.com/guides)
