# Certificate Infrastructure

[![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)](https://choosealicense.com/licenses/mit/)
![commit history](https://img.shields.io/github/last-commit/cdcgov/ocio-certificates?label=commits&style=for-the-badge)

> [!TIP]
> Go directly to the [data/bundle/README](./data/bundle/README.md) to find selective certificate bundles to download.

Certificate authorities (CAs) are entities that issue digital certificates, which are used to verify the authenticity of a website or entity on the internet. These certificates establish trust in online communications by confirming that a website or service is what it claims to be and by encrypting and securing the data exchanged between the user and the server.

We use digital certificates to sign code, to serve as a medium for identity (ex. PIV cards) and to identify an asset (ex. client or server identification with an SSL/TLS certificate).

This repository exists to provide the [latest certificates](./data/bundle/README.md) that clients and servers should install and trust by default and to remediate any verification problems in SSL/TLS connections when accessing internal CDC websites or crossing CDC firewalls.

Digital certificates in .pem format are akin to _public keys_ and do not contain sensitive information.

For more technical knowledge, view [technical.md](docs/technical.md).
