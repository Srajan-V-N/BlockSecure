# BlockSecure  
## Secure Digital and Physical Evidence Management System

---

## 1. Overview

**BlockSecure** is a comprehensive digital and physical evidence management system designed to ensure secure collection, decentralized storage, integrity verification, continuous monitoring, and controlled access of forensic evidence. The platform integrates **IPFS-based distributed storage**, **blockchain-backed integrity anchoring**, and an intelligent evidence processing pipeline (**HybridNetX**) to preserve evidence authenticity and maintain a verifiable **chain of custody** throughout the entire evidence lifecycle.

The system is architected to reflect real-world forensic workflows, combining structured digital evidence handling, physical evidence governance, multi-factor access control, continuous integrity monitoring, and audit-grade traceability.

---

## 2. Core Objectives

- Ensure tamper-resistant storage of digital evidence  
- Maintain a verifiable chain of custody for physical evidence  
- Automate evidence processing and storage optimization using **HybridNetX**  
- Provide controlled, role-based, auditable access to sensitive evidence  
- Enable visual and cryptographic authenticity verification  
- Continuously monitor evidence integrity and availability  

---

## 3. System Architecture Overview

BlockSecure is composed of the following major subsystems:

- Authentication and Role Management  
- Case Management  
- Digital Evidence Management  
- HybridNetX Intelligence Pipeline  
- Physical Evidence Management  
- Evidence Authenticity Verification  
- Continuous Integrity Monitoring Service  
- Audit and Access Logging  

Each subsystem operates cohesively to ensure integrity, accountability, availability, and traceability.

---

## 4. Authentication and Role Management

The platform enforces secure authentication with predefined roles, including:

- Investigating Officer  
- Forensic Analyst  
- Judiciary / Authorized Reviewer  

All interactions are governed by **role-based access control (RBAC)**. Every system action is associated with a verified identity and recorded to ensure non-repudiation and auditability.

---

## 5. Case Management

The Case Management module enables:

- Creation and management of investigation cases  
- Assignment of case attributes such as type, priority, and geographical location  
- Association of both digital and physical evidence with a case  
- Tracking of case updates and investigation progress  

Each case serves as the authoritative container for all related evidence and actions.

---

## 6. Digital Evidence Management

### 6.1 Evidence Upload and Storage

BlockSecure supports secure upload of digital evidence including documents, images, videos, and audio files. During upload:

- A cryptographic hash (SHA-256) is computed  
- Evidence is processed by the **HybridNetX pipeline**  
- Optimized chunks are stored on **IPFS**  
- The resulting CID and hash are anchored on the blockchain  

This ensures immutability, decentralized storage resilience, and verifiable integrity.

---

### 6.2 Evidence Metadata Management

Each digital evidence item is associated with structured metadata including:

- Case ID  
- Evidence description  
- Evidence type  
- Geographical location of relevance  
- Contextual tags  
- Upload timestamp  
- Uploader identity  

Metadata enhances traceability and contextual understanding without exposing raw evidence.

---

## 7. HybridNetX Intelligence Pipeline

**HybridNetX** is the internal intelligence layer responsible for optimizing evidence storage and processing decisions before committing data to decentralized storage.

### 7.1 Textual Feature Processing

For document-based evidence, HybridNetX applies a structured machine learning pipeline:

- **TF-IDF (Term Frequency–Inverse Document Frequency)**  
- **SVD (Singular Value Decomposition)**  
- **FFNN (Feed-Forward Neural Network)**  

This pipeline enables intelligent evidence characterization without altering original evidence content.

---

### 7.2 HybridNetX Optimization Features

HybridNetX enforces four core optimization mechanisms:

- **Adaptive Chunking**  
- **Redundancy Control**  
- **Deduplication**  
- **Gateway Selection**  

These mechanisms collectively improve storage efficiency, scalability, and retrieval reliability.

---

## 8. Physical Evidence Management

BlockSecure extends beyond digital assets to manage physical evidence such as weapons, documents, devices, or forensic materials.

### 8.1 Physical Evidence Registration

- Each physical item is registered under a specific case  
- A unique QR code is generated for identification  
- Metadata includes storage location, item description, collector details, and consent requirements  

---

### 8.2 Physical Evidence Access Control Workflow

Access to physical evidence is protected through a multi-step verification workflow:

1. Physical Evidence QR Code Scan  
2. Officer Badge QR Code Scan  
3. Officer Passkey Authentication  
4. Intent of Access Declaration  

Only after successful completion of all steps is access granted. Every access attempt is fully logged.

---

## 9. Evidence Authenticity Verification

BlockSecure includes a dedicated module to validate whether an evidence file has been altered.

- Side-by-side comparison of original and suspect evidence  
- Cryptographic hash validation against blockchain records  
- Heatmap-based visual comparison highlighting modified regions  

---

## 10. Continuous Integrity Monitoring Service

BlockSecure implements a continuous monitoring service to ensure long-term evidence integrity and availability.

- Periodic verification of IPFS CID availability  
- Detection of missing or unreachable evidence  
- Recalculation and comparison of cryptographic hashes  
- Logging and flagging of integrity anomalies  

This service enables proactive detection of evidence loss or tampering.

---

## 11. Audit Logging and Traceability

- All uploads, accesses, verifications, and monitoring events are logged  
- Logs capture user identity, action type, evidence reference, and timestamp  
- Supports audits and compliance verification  

---

## 12. Technology Stack

- **Frontend:** React  
- **Backend:** Flask  
- **Database:** MongoDB  
- **Decentralized Storage:** IPFS  
- **Blockchain:** Hyperledger Fabric  
- **Machine Learning:** TF-IDF, SVD, FFNN  

---

## 13. Project Files and Storage Notice

Due to GitHub’s 100 MB file size limitation, the complete BlockSecure project (~7 GB) is not fully hosted on GitHub.

### Full Project Access

The complete project folder is available via Google Drive:

**Google Drive Link:**  
`<PASTE LINK HERE>`

---

## 14. License

This project is intended for academic and research purposes.
