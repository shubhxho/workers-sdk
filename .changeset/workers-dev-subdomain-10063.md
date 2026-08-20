---
"wrangler": patch
---

Point error 10063 at the Workers onboarding page

When an account has no workers.dev subdomain, the API returns 10063 and tells you to "open the Workers menu". Wrangler now also prints the onboarding URL that actually creates the subdomain.
