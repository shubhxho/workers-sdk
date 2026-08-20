---
"miniflare": patch
"wrangler": patch
---

Explain how to populate Secrets Store secrets in local dev

`env.SECRET.get()` in `wrangler dev` threw `Secret "…" not found` when the value only existed remotely. The error now says remote secrets are not copied into local storage, and points at `wrangler secrets-store secret create` without `--remote`.
