# Certificate Bundles

A .pem formatted certificate is human-readable in base64 format, and starts with the lines **----BEGIN CERTIFICATE----**. A certificate bundle, usually in .crt format includes a number of these certificates, is also human-readable in base64 format with a list of certificates.

| Certificate Bundles     | What does the bundle have?                                                                  |
| ----------------------- | ------------------------------------------------------------------------------------------- |
| [min-cdc-bundle-ca.crt] | Includes minimum certificate bundle with CDC internal self-signed and firewall certificates |

## Usage

- View [technical.md #usage](../docs/technical.md#usage).

[min-cdc-bundle-ca.crt]: ./min-cdc-bundle-ca.crt
