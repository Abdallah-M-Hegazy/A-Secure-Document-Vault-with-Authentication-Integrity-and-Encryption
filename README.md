# SecureDocs – A Secure Document Vault with Authentication, Integrity, and Encryption

SecureDocs is a web-based platform for secure document management, built to ensure data confidentiality, integrity, and controlled access. Designed for use in legal, HR, and enterprise environments, it provides:

## 🔐 Authentication & Access Control

- OAuth 2.0 login via Google and GitHub

- Enforced Two-Factor Authentication (2FA) using TOTP

- Session-based login with token expiration

- Role-Based Access Control (RBAC) with user/admin roles

## 📁 Secure Document Vault

- Upload and manage documents (PDF, DOCX, TXT)

- AES-encrypted storage

- SHA-256 hashing and HMAC/CRC for integrity checks

- Digital signatures and signature verification via OpenSSL

## 👤 User & Admin Features

- Users: upload/download/sign documents, manage profiles

- Admins: manage users, roles, logs, and all documents

## 🌐 Secure Transmission

- HTTPS support via local SSL/TLS setup with OpenSSL

- Protection against MITM attacks (demonstrated via Wireshark)

## 🎨 Modern Responsive UI

- Clean design using Bootstrap or Tailwind

- Role-based UI rendering and route protection
  
--- 

This project applies real-world security practices to deliver a robust document management system with end-to-end protection.
