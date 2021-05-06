### PKI

PKI infrastructure for a surprisingly interesting networks class.

PKI consists of: root CA and signing CA.

Example:
- An org controls a domain flash.xyz
- Org decides to run a small PKI to secure email and intranet traffic
- We need a Root CA and its CA certificate.
- We use root CA to create Simple Signing CA
- Issue out email and TLS certs to the webservers

