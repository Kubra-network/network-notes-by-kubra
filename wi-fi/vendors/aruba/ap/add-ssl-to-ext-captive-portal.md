# Uploading SSL Certificate to IAP for External Captive Portal Configuration

External captive portal creates the SSL cert to be trusted by the network devices and sends them to check the cert.

By uploading the SSL certificate to the IAP, you ensure that the IAP can present the correct certificate to clients during the captive portal authentication process, thus avoiding certificate mismatch or trust issues.

Client devices check the IAP or controller or Central (based on your topology) for the captive portal cert check & trust.

Network devices check the cert and let clients connect to captive portal.
