# JWT

## Using asymmetric encryption (Ed25519)

You need to generate private and public keys:

```
openssl genpkey -algorithm ed25519 -out private.pem
openssl pkey -in private.pem -pubout -out public.pem
```
