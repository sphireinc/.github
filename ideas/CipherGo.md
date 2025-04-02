# CipherGo – Go-Powered Cryptography & Secure Storage Toolkit  

## Overview  
CipherGo is a **Go-based cryptography and secure storage toolkit** designed to simplify encryption, hashing, and secure data management for developers. It provides **easy-to-use abstractions** over complex cryptographic primitives, making it ideal for applications that require **secure data transmission, encryption at rest, and authentication mechanisms**.  

## Key Features  

### 🔐 Pluggable Encryption Algorithms  
- **AES** (128, 192, 256-bit)  
- **RSA** (2048, 4096-bit)  
- **ECDSA & Ed25519** (Elliptic Curve Signatures)  
- **Post-Quantum Cryptography** (e.g., Kyber, Dilithium) *(Experimental)*  

### 🛠 Secure Storage Helpers  
- **Encrypted file storage** for JSON, YAML, and raw data  
- **Secret management** (password vault, API key storage)  
- **Database encryption** support for PostgreSQL, MySQL, SQLite  

### 🔑 Authentication & Key Management  
- **JWT signing and verification**  
- **OAuth2 token encryption**  
- **Key exchange & derivation** (PBKDF2, Argon2, bcrypt, scrypt)  

### 🌐 Network Security & Data Transmission  
- **TLS certificate generation & management**  
- **End-to-end encryption (E2EE) for WebSockets, APIs**  
- **Secure tunnels for microservices & distributed apps**  

### 🖥 HSM (Hardware Security Module) & TPM Support  
- **Pluggable backend for using hardware-based key storage**  
- **Integration with YubiKeys, smart cards, and cloud HSMs**  

## Use Cases  
✅ Secure API authentication (JWT, OAuth)  
✅ Encrypted databases (e.g., protect user data at rest)  
✅ End-to-end encrypted messaging & file sharing  
✅ Secure cloud applications & microservices  
✅ Password vaults & cryptographic key management  
