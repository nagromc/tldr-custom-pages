- Generate a local dev CA certificate:

`openssl req -x509 -nodes -newkey {{rsa}}:{{2048}} -keyout {{dev-ca-key.pem}} -out {{dev-ca-cert.pem}} -subj {{"/CN=local dev root CA"}} -days {{3650}}`
