---
description: Fast, secure authentication for residents made easy.
---

# End User Guide

In this user guide, we are taking an example of a health services portal that acts as a relying party using eSignet to provide services and benefits to the residents. Also, in turn, the residents can quickly identify themselves using their country's foundation ID system (here MOSIP), thereby avoiding the hassles of repeatedly filling up their account or personal information.

There are multiple ways in which user authentication can be done.

Before starting with the login flows, let us understand the following terms:

1. **Essential claims:** These are mandatory user information required by the relying party to be able to provide their services to the residents.
2. **Voluntary claims:** They are additional user information that residents can choose to share to get some add-on features for the service provided by the relying party.

With this release, we support the login flow for the following authentication factors:

1. [Login with Password](health-portal/login-with-password.md)
2. [Login flow for OTP-based authentication](health-portal/login-with-otp.md)
3. [Login flow for Biometrics based authentication](health-portal/login-with-biometrics.md)
4. [Login flow with QR code (Inji)](health-portal/login-with-qr-code.md)
5. [Knowledge Based Identification](health-portal/knowledge-based-authentication.md)
6. [Sign up and Login with OTP for Verified Claims](../../../esignet-signup/test/end-user-guide/signup-and-login-with-otp-for-verified-claims.md)

> Note: The screenshots and the steps mentioned in each of the flows are for demonstration purpose only and are likely to change based on the use case.

In the login flows mentioned above, the authorization code flow is used to fetch the user profile based on the consent.
