# openssl verify

> OpenSSL command to verify certificate chains.
> More information: <https://docs.openssl.org/master/man1/openssl-verify/>.

- Verify that a certificate has been issued by the given CA:

`openssl verify -CAfile {{CA_certificate_file}} {{issued_certificate_file}}`

- Show certificate chain of a given CA:

`openssl verify -show_chain -CAfile {{CA_certificate_file}} {{issued_certificate_file}}`
