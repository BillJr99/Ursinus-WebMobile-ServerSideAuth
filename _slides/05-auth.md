---
transition: zoom
---

## Verifying a jwt in node.js

- [Tutorial](https://www.sohamkamani.com/blog/javascript/2019-03-29-node-jwt-authentication/)

```javascript
const jwt = require("jsonwebtoken")
// obtain token from body request or cookie
payload = jwt.verify(token, "secret key"); 
// try/catch the above to return an HTTP error should validation fail
```

If authentication fails:

```javascript
return res.status(401).end(); // unauthorized
```