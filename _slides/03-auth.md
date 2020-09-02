---
transition: zoom
---

## Authentication

- If you authenticate a user, you can send them a jwt containing a JSON document of their username.
- They provide that key back to you on each request.
- You can verify the key by decrypting the signature with your public key and matching it against the payload.