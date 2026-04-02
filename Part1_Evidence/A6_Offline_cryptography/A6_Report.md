# A6 — Discover Cryptography Implementation Used Offline

# Objective
The purpose of this activity is to identify and demonstrate cryptographic implementations that operate offline on a personal computing device. Offline cryptography refers to security mechanisms that protect data locally without requiring an internet connection.

# Description of Activity
In this task, cryptographic security features available on a macOS device were explored. The investigation focused on identifying encryption and authentication mechanisms that function locally on the system.

Several built-in macOS security components were examined to understand how cryptography protects user data, device access, and storage.

# Evidence Collected

# 1. FileVault Disk Encryption
FileVault provides full-disk encryption using advanced cryptographic algorithms. It ensures that all data stored on the device is encrypted and inaccessible without authentication.

**Evidence:** Screenshot showing FileVault enabled in system settings.

# 2. Touch ID Authentication
Touch ID uses biometric authentication secured by Apple's Secure Enclave. Biometric data is encrypted and stored locally, allowing secure authentication without internet connectivity.

**Evidence:** Screenshot of Touch ID configuration settings.

# 3. Local User Password Authentication
User login credentials are protected using cryptographic hashing mechanisms. Authentication occurs locally on the device before granting access to the system.

**Evidence:** Screenshot of Users & Groups settings.

# 4. Disk Utility Encryption Structure
Disk Utility demonstrates encrypted storage containers used by macOS file systems. These encrypted volumes protect stored data through cryptographic techniques.

**Evidence:** Screenshot of Disk Utility showing internal storage.

# Cryptographic Concepts Identified
- Full Disk Encryption (FileVault)
- Biometric Authentication
- Password Hashing
- Secure Key Storage
- Encrypted File Systems

# Outcome
This activity demonstrated that cryptography is widely implemented at the operating system level to secure data and user authentication offline. These protections operate independently of network connectivity, ensuring device security even when disconnected from the internet.

# Conclusion
Offline cryptographic mechanisms play a critical role in protecting sensitive information. The macOS system integrates multiple encryption technologies that safeguard data confidentiality, integrity, and access control through local cryptographic processes.
