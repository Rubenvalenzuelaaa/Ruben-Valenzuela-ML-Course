# Midterm Project – Cybersecurity for AI-Integrated IIoT Systems

## Objective
The goal of this project was to design a comprehensive cybersecurity framework for a smart manufacturing facility integrating AI and IIoT technologies.

## System Overview
The system includes:
- PLCs, sensors, robotic arms (OT layer)
- Edge AI nodes for real-time inference
- Network infrastructure with segmentation and firewalls
- Cloud services (AWS IoT Core, S3, SageMaker)
- Human operators and administrative systems

## Key Work Done
- Designed a full IIoT system architecture (Purdue Model adaptation)
- Identified 17 vulnerabilities across multiple layers
- Classified vulnerabilities by severity (Critical, High, Medium)
- Developed a layered defense strategy based on NIST CSF 2.0
- Simulated cyberattacks (penetration testing)
- Evaluated system resilience and identified weak points

## Security Risks Identified
- Default PLC credentials
- Weak network segmentation
- Misconfigured cloud storage (S3)
- AI data poisoning attacks
- Human vulnerabilities (phishing, weak passwords)

## Defense Strategy
- Multi-Factor Authentication (MFA)
- Role-Based Access Control (RBAC)
- Network micro-segmentation
- End-to-end encryption (TLS, AES-256)
- AI model validation and adversarial protection
- Zero Trust architecture principles

## Results
- 3 attacks blocked
- 2 attacks successful
- 1 partially mitigated

## Key Insight
Security in AI-integrated IIoT systems must address not only infrastructure, but also AI models and human behavior.

## Technologies & Concepts
- Cybersecurity (NIST CSF 2.0)
- IIoT Systems
- AI Security
- Network Security
- Cloud Security (AWS)
- Zero Trust Architecture

## Files Included
- PowerPoint Presentation (.pptx)
- Full Written Report (.docx)
