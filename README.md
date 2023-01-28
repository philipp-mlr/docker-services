> # TLS
> the crt files only work if:
> - domain.crt is a chain/- or full-chain certificate in which domain, intermediate, and root-ca have been joined

`cat domain.crt intermediate.crt ca-root.crt > chain.crt`

> - the private key must be unencrypted
