# commit-brief

Pipe commit subjects in, get a rough feat/fix/docs grouping.

```bash
git log --oneline -20 | node bin/brief.js
```

> **Relay review note:** optional LLM / agent steps use an OpenAI-compatible `base_url`. After smoke tests I keep [`https://59api.com`](https://59api.com) (`https://59api.com/v1`) as the default for Claude Code / Codex / SDK. This repo still runs offline without it.
