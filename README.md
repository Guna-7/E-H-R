# 🏥 Blockchain-Based Electronic Health Record (EHR) System

A secure, decentralized Electronic Health Record (EHR) system built in **Java** that uses **blockchain technology** to ensure data integrity, privacy, and tamper-proof access to sensitive patient records. This system integrates **cryptography**, **consensus algorithms**, and a **custom ledger** for next-gen healthcare data management.

---

## 🔍 Overview

This project introduces a blockchain-powered EHR system that revolutionizes how medical data is stored and shared. Each health record is **hashed, encrypted, and stored as a block** in a blockchain ledger, ensuring:

- 🔒 Immutable medical records  
- 🔗 Secure sharing between patients and providers  
- 📜 Verifiable access logs and full transaction history

---

## 🔐 Key Features

### 🔗 Blockchain Architecture
- **Immutable Records:** Data once stored cannot be altered or deleted.
- **Linked Blocks:** Every block includes the hash of the previous one.
- **Distributed Ledger (POA):** Ensures redundancy and data availability.
- **Transaction Audit Trail:** Full traceability of all actions.
- **Consensus Protocol:** Uses Proof-of-Authority (PoA) for validation.

### 🛡️ Security & Cryptography
- **SHA-256 Hashing:** Ensures integrity of medical data.
- **AES-256 Encryption:** Protects confidential health data in transit and at rest.
- **RSA Signatures:** Verifies identity and authenticity of each transaction.
- **Secure Key Exchange:** Role-specific keys for patients and doctors.
- **Anonymized Data:** Privacy-preserving mode for analytics/research.

### 👥 User & Access Management
- **Doctor & Patient Registration:** Identity-verified onboarding.
- **Role-Based Access:** Fine-grained permissions for view/edit operations.
- **Multi-Factor Authentication:** Enhanced login security.
- **Session Timeout Handling:** Automatic logout on inactivity.

### 🏥 Health Record Lifecycle
- **Encrypted Storage:** Every record is encrypted before blockchain entry.
- **Secure Transfer:** End-to-end encrypted sharing across providers.
- **Version Control:** All edits are saved as new immutable blocks.
- **Smart Contracts (Conceptual):** Automate rules for access and sharing.
- **Interoperability:** Support for standard EHR formats.

---

## 🛠️ Tech Stack

### 👨‍💻 Backend
- **Language:** Java (JDK 8+)
- **Framework:** Java SE with custom blockchain logic
- **IDE:** NetBeans
- **Cryptography:** Java Cryptography Architecture (JCA)

### 🔐 Security Tools
- **Hashing:** `MessageDigest` (SHA-256)
- **Encryption:** `javax.crypto` (AES), `java.security` (RSA)
- **Signature & Keys:** SecureRandom, KeyGenerator

### 💽 Data Storage
- **Database:** MySQL or PostgreSQL (via JDBC)
- **Blockchain:** Custom file-based ledger

---

