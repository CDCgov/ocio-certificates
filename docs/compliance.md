# Compliance Knowledge

## Public Hosting

To host a _public_ federal government website, the [https.cio.gov website](https://https.cio.gov/certificates/) explains the HTTPS/SSL/TLS requirements. Besides getting a SSL/TLS certificate, federal government guidelines have [additional compliance regulations](https://https.cio.gov/guide/). These may include website to redirect all HTTP traffic on port 80 to HTTPS on port 443 by default, setting up HSTS, using server name indication (SNI).

At CDC, we purchase public certificates signed by the [Entrust](https://docs.cdc.gov/docs/devsecops/services/certificate-management/entrust) commercial vendor, who is a certificate authority for the public internet, and normally, ask that public domains that serves content to go through the [Akamai](https://akamai.com) vendor, who fulfills the purpose of a Content Delivery Network (CDN) and a Web Application Firewall (WAF).
