# repo-gardener-website

Landing page for [repo-gardener](https://github.com/agent-team-foundation/repo-gardener) — a context-aware review bot for GitHub PRs and issues.

## Stack

- Single static `index.html`
- No build step, no framework
- Inter + JetBrains Mono fonts via Google Fonts
- Deployed on Vercel

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Push to `main`. Vercel auto-deploys.

## License

Apache 2.0
