# cergy-server-reverse-proxy# Generate quick ssl certificates
openssl req -x509 -newkey rsa:4096 -keyout certs/key.pem -out certs/cert.pem -sha256 -days 365 -nodes
