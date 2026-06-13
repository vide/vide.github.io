# vide.github.io

Personal GitHub Pages site.

## Tesla Fleet API public key

`/.well-known/appspecific/com.tesla.3p.public-key.pem` is the EC (P-256)
public key for the Tesla Fleet API developer application registered for
TeslaMate. Tesla fetches it to validate ownership of this domain.

The matching private key is **not** in this repo — it is kept offline.

`.nojekyll` disables Jekyll so the `.well-known` directory (which Jekyll
would otherwise ignore because it starts with a dot) is published.
