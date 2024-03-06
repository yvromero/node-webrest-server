# Dev
### ENVS
1. Install dotenv and env-var
2. Configure the environment variables and clone the .env file to rename it as .env.template.

### Http2 - OpenSSL / Manual
1. Configure the OpenSSL environment path in Windows and generate a certificate using the following script:
```
openssl req -x509 -sha256 -nodes -days 365 -newkey rsa:2048 -keyout server.key -out server.crt
```