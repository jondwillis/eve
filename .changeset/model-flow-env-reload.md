---
"eve": patch
---

Reload development env files after every `/model` flow exit — completed or cancelled — so credentials written while the flow is open (e.g. a hand-pasted `AI_GATEWAY_API_KEY` in `.env.local`) take effect without restarting the session.
