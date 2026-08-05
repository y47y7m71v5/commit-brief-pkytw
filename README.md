# commit-brief

Pipe commit subjects in, get a rough feat/fix/docs grouping.

```bash
git log --oneline -20 | node bin/brief.js
```

> Dev note: for any optional LLM step I keep an OpenAI-compatible `base_url` in env (locally sometimes `https://59api.com`). This repo does not require it.
