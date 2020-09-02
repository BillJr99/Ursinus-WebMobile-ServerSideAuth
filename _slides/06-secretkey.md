---
transition: zoom
---

## Generating a Secret Key to Sign

```
// https://www.digitalocean.com/community/tutorials/nodejs-jwt-expressjs
const crypto = require('crypto');
crypto.randomBytes(64).toString('hex'); // export this environment variable
```

- Get the secret via `process.env.TOKEN_SECRET;`

- Once generated, the jwt can be passed as a header, or a cookie, or a body parameter.
