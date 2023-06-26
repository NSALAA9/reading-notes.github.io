

What is a JSON Web Token (JWT)?
- JWT is a compact and self-contained way of transmitting information between parties as a JSON object.

When should we use JSON Web Tokens?
- JWTs are commonly used in authentication and authorization scenarios, where a user logs in and subsequent requests include the token to prove their identity and access privileges.

Claims are expected in which structural component of a JWT?
- Claims are expected in the payload component of a JWT.

If I get a JWT and I can decode the payload, how can we call that secure?
- The security of a JWT lies in the signature. If the signature is valid, it ensures that the token hasn't been tampered with and comes from a trusted source.

If sending a JWT, what must the sender and receiver both know? Hint, it’s appended in the signature.
- The sender and receiver must both know the secret key that is used to create and verify the signature.

Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
- The concatenated content and secret can be encrypted using a secure algorithm and transmitted over a secure channel to ensure secure transmission. The non-technical recruiter must have the knowledge of how to decode the JWT and understand the meaning of the claims to effectively use the information.

Why use JWT?
- JWTs are compact and self-contained, making them efficient to transmit and eliminating the need for additional database or session lookups. They are portable and convenient for exchanging information between systems or microservices.

JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
- JWTs being compact means they are efficient to transmit, reducing bandwidth and latency. Being self-contained means all necessary information is within the token itself, eliminating the need for additional lookups or dependencies.

What are the three components (the structure) of a JWT signature?
- The three components of a JWT signature are the header, payload, and secret key. The header contains information about the token, the payload carries the claims, and the secret key is used to create the signature for integrity verification.
