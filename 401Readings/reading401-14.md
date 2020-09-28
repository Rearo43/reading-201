# Access Control (ACL)

#### When is Basic Authorization used vs. Bearer Authorization?
  > Basic authentication schemes are used to authenticate using a username and a secret. The Bearer authentication scheme is used to the authenticate using a token.
#### What does the JSON Web Token package do?
  > Compact URL-safe means of representing claims to be transferred between two parties. 
#### What considerations should we make when creating and storing a SECRET?
  > Who has access to where it's being stored and using it in a dotenv file.

### Terms
- encryption: method by which information is converted into secret code that hides the information's true meaning
- token: credentials to gain access to that part of the site
- bearer: whenever the user wants to access a protected route or resource, the user agent should send the JWT, typically in the Authorization header using the Bearer schema
- secret: JWTs can be signed using a secret
- JSON Web Token: JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.
