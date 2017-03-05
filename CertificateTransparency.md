# Certificate Transparency (CT)
@crypto @crypto-engineering @authentication @pki

* CT's goal is to increase accountability and monitoring of the CA system.

* Three core components: Certificate Logs, Auditors, Monitors.

## Certificate Logs

* Logs are an append-only record of certificates.

* Most submitters to logs will be CAs but its not required.

## Monitors

* Monitors are servers that periodically contact all logs and watch for suspicious certificates.

* "A monitor acts much the same way as a credit-reporting alert, which tells you whenever someone applies for a loan or credit card in your name." [What is Certificate Transparency]

## Auditors

*  Auditors are "lightweight" and perform two functions:

    1. They verify that logs are "behaving correctly" and are "cryptographically consistent".

    2. They can check that a particular certificate appears in a log.

# References

* [What is Certificate Transparency?](https://www.certificate-transparency.org/what-is-ct)

* [Certificate Transparency in Chrome](https://www.chromium.org/Home/chromium-security/certificate-transparency)
