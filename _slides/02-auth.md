---
transition: zoom
---

## Authentication

- Java Web Tokens ([jwt](https://www.sohamkamani.com/blog/javascript/2019-03-29-node-jwt-authentication/))

```
header.payload.signature
```

- Header: boilerplate information about the signature algorithm
- Payload: The actual key information
- Signature: The digital signature is the header and payload signed with a private key
- Each element is Base-64 encoded