# A5 — Cryptographic Implementation Online

# Objective
To discover and document cryptographic implementation used in online services, demonstrating secure communication via encryption protocols.

# Observation
I examined the website **[insert website name, e.g., Gmail]**. The URL shows `https://` and a padlock icon indicating a secure connection. Clicking the icon shows **valid TLS/SSL certificate information**.

**Evidence:** 1_HttpsCertificate.png

# Security Purpose
The HTTPS connection uses **TLS encryption**, which ensures:
- **Confidentiality** — data between the client and server is encrypted.  
- **Integrity** — messages cannot be tampered with during transmission.  
- **Authentication** — ensures the website is genuine, verified by a trusted certificate authority.

# Reflection
This activity demonstrates that even everyday websites implement cryptography to protect user data. Understanding these implementations reinforces the importance of **encryption in securing online communication** and the value of HTTPS for all web services.
