openssl-selfsign
===================

Set of configuration/script to make self-signed certificates.

This distribution is based on that of Red Hat Enterprise Linux Server release 5.1.

## Set

* openssl.cnf.ca
  * An OpenSSL configuration for making the self CA certificate
* openssl.cnf.sign
  * An OpenSSL configuration for signing a server certificate with the self CA certificate
* openssl.cnf.req
  * An OpenSSL configuration for requesting a self server certificate
* misc/CA
  * A script to execute either making a CA cert, signing, or request a cert, with configurations the above.

