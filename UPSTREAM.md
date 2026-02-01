# Upstream Sync

This is a fork of [openclaw/openclaw](https://github.com/openclaw/openclaw).

## Remotes

| Remote | Repository | Purpose |
|--------|------------|---------|
| origin | ebiyy/openclaw | Your fork (push here) |
| upstream | openclaw/openclaw | Original repo (pull from here) |

## Sync Commands

```bash
# Fetch and rebase upstream changes
git fetch upstream
git rebase upstream/main
git push origin main
```

## Related Fork

- [ebiyy/moltworker](https://github.com/ebiyy/moltworker) - Cloudflare Workers wrapper (upstream: cloudflare/moltworker)

moltworker uses this package as `clawdbot` npm dependency.
