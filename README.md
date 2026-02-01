# Privacy Policy for Auth Guard

**Effective Date:** February 1, 2026
**Last Updated:** February 1, 2026

### 1. Information We Collect
To provide security and server backup services, **Auth Guard** collects the following data when you authorize the application via OAuth2:
* **Discord User ID:** To identify your account uniquely.
* **Username and Discriminator:** To log verification attempts.
* **Access Tokens:** Encrypted tokens specifically for the `guilds.join` scope.

### 2. How We Use Your Information
We use your data strictly for the following:
* **Verification:** To confirm your account meets security requirements (e.g., account age of 10+ days).
* **Server Redundancy:** To automatically add authorized users to a backup server if the primary server is deleted or compromised.
* **Abuse Prevention:** To block disposable emails and restricted VPN/Proxy connections.

### 3. Data Storage and Security
* **Storage:** Data is stored in a private database accessible only by the bot's developers.
* **Encryption:** Access tokens are encrypted at rest.
* **Revocation:** You may revoke access at any time through your Discord settings under **User Settings > Authorized Apps**. Doing so invalidates our token immediately.

### 4. Third-Party Sharing
**Auth Guard** does not sell, trade, or share your data. We do not use your data for marketing or tracking outside the scope of server security.

### 5. Contact
For data deletion requests, please contact the Server Administrator by using `.contact` command.
