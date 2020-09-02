---
transition: zoom
---

## Creating a jwt in node.js

- [Tutorial](https://www.sohamkamani.com/blog/javascript/2019-03-29-node-jwt-authentication/)

```javascript
const jwt = require("jsonwebtoken")
const token = jwt.sign({ username }, "secret key", { algorithm: "HS256", expiresIn: 300});
```

If authentication fails:

```javascript
return res.status(401).end(); // unauthorized
```