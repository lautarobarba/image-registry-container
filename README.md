# Docker registry

## SSL

```bash
$ openssl req -newkey rsa:4096 -nodes -sha256 -addext "subjectAltName = DNS:registry.desarrollosur.com.ar" -keyout domain.key -x509 -days 3650 -out domain.crt
```
