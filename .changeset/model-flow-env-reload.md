---
"eve": patch
---

Refresh the dev TUI's model-access view after every `/model` flow exit — completed or cancelled. Cancelling `/model` after writing an `AI_GATEWAY_API_KEY` into `.env.local` no longer leaves a stale "model provider not linked" attention line; the runner reloads env and re-reads agent info on the way out.
