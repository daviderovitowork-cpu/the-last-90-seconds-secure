# THE LAST 90 SECONDS — Secure Backend

Private server for the cinematic interactive anthology by Matchka Network Solutions.

## SECURITY: NOT READY TO DEPLOY

**This repository is currently PUBLIC.** Do not commit backend source, paid story scripts, API credentials, buyer details, databases, or live Stripe configuration until its visibility is changed to **Private** and verified.

GitHub: Settings → General → Danger Zone → Change repository visibility → Make private.

The V11.2 package is staged separately. Deployment must remain blocked until:
- repository visibility is **private**;
- only the isolated `TL90 Secure Staging` Railway environment is targeted;
- persistent database, email delivery, domain/HTTPS, and Stripe **test mode** are correctly configured;
- all checkout flags remain off pending signed-webhook and refund end-to-end checks;
- premium stories are removed from publicly served Wix files before charging anyone.

**No live payments. No customer data in this repository.**
