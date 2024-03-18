![gopher-gang](https://github.com/ildx/snippetbox/assets/4620010/37587aa3-970b-48ac-a55b-6e5297aa690f)

# Snippetbox
Web app for pasting and sharing snippets of text. Based on the book [Let's Go!](https://lets-go.alexedwards.net/) by Alex Edwards.

## TLS
To generate a self-signed certificate for local development, run the following command:
```bash
go run /PAHT_TO_YOUR_GO_INSTALLATION/go/src/crypto/tls/generate_cert.go --rsa-bits=2068 --host=localhost
```
