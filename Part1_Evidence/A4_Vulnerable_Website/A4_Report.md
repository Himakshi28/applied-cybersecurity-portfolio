
# Activity A4 — Discover a Vulnerable Website

# Website Analysed
http://neverssl.com

# Objective
The purpose of this activity was to identify and analyse a real-world website demonstrating a cybersecurity vulnerability.

# Observed Vulnerability
The website uses HTTP instead of HTTPS for communication.

HTTP does not encrypt data transmitted between the user and the web server. As a result, information exchanged can potentially be intercepted or modified by attackers performing a Man-in-the-Middle (MITM) attack.

# Evidence Collected
- Screenshot showing HTTP connection in browser address bar.
- Screenshot showing browser security warning (“Not Secure”).

# Security Risk Analysis
Because encryption is not used:
- Data can be read by attackers on the same network.
- User privacy is not protected.
- Session information may be exposed.
- Users may be vulnerable on public Wi-Fi networks.

Modern cybersecurity standards recommend HTTPS with TLS encryption to ensure confidentiality and integrity of communication.

# Mitigation Recommendation
The website should implement HTTPS using TLS certificates and automatically redirect HTTP traffic to HTTPS.

# Reflection
This activity helped me understand how browsers visually indicate insecure connections and why encrypted communication is essential for protecting users online.
