# Nishchint Backend

This repository contains the backend services for the Nishchint Digital Evidence Vault platform.

## Project Overview
The backend is responsible for securely handling digital evidence uploads, generating cryptographic hashes for integrity verification, managing metadata, and providing APIs for the frontend interface.

## Core Features
- Secure file upload API
- Cryptographic hash generation (SHA-256)
- Evidence integrity verification
- Metadata storage for uploaded evidence
- API endpoints for frontend communication

## Technologies Used
- Python (FastAPI / Flask)
- RESTful API architecture
- Cloud storage for evidence files
- Database for metadata storage (Firebase / MongoDB / PostgreSQL)

## System Architecture
The backend exposes REST APIs that allow the frontend to:
- Upload evidence files
- Retrieve hash values
- Verify file integrity
- Store and fetch evidence metadata

## Security Considerations
- Hash-based integrity verification
- Secure API endpoints
- Separation of file storage and metadata database
- Future implementation of authentication and access control

## Deployment Plan
The backend will be deployed on a cloud hosting platform such as Render or Railway.  
APIs will be publicly accessible and connected to the frontend hosted on Vercel.

## Future Enhancements
- User authentication and role-based access control
- Blockchain-based hash immutability
- Automated legal report generation
- Audit logs for evidence access and modification tracking

