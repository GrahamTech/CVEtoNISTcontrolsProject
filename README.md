Project Title:
Automated Vulnerability Mapping and Security Control Assignment

Brief Description:
This project automates the process of mapping cybersecurity vulnerabilities (CVE data) to relevant NIST 800-53 security controls. By leveraging natural language processing (NLP) techniques and machine learning algorithms, the system categorizes vulnerabilities, assesses their severity, and recommends specific security controls to mitigate associated risks. It simplifies vulnerability management for organizations, ensuring that threats are addressed with appropriate security measures, and enhances compliance with industry standards.

The project consists of a few key components:

Natural Language Processing (NLP):

The system processes and analyzes vulnerability descriptions (CVE data) to identify key characteristics such as attack type, risk, and impact.
Keyword-based mapping: Vulnerabilities containing specific keywords (e.g., "SQL Injection", "Buffer Overflow") are mapped to predefined NIST controls.
Topic modeling: Using machine learning (LDA), the system categorizes vulnerabilities into broader topics, such as "Remote Code Execution" or "Privilege Escalation", to apply more relevant security controls.

Risk Assessment Using CVSS Scores:

The system evaluates each vulnerability's severity using its CVSS (Common Vulnerability Scoring System) score. Vulnerabilities are prioritized based on their potential risk, ensuring that critical issues receive appropriate attention.
Dynamic control assignment: The system applies stricter security controls for vulnerabilities with higher CVSS scores, addressing high-risk issues with more robust measures.

Automated Mapping to NIST 800-53 Security Controls:

Each vulnerability, based on its description, topic, and severity, is automatically mapped to one or more NIST 800-53 security controls.
Enhanced controls are applied for specific high-risk vulnerabilities to ensure better coverage and protection.

Key Functions:
Vulnerability Classification:

The system processes vulnerability descriptions using NLP techniques to classify them into relevant security categories.
Functionality: Identifies key terms like “Privilege Escalation” or “SQL Injection” to determine the nature of the vulnerability.

Topic Modeling:

Uses Latent Dirichlet Allocation (LDA) to categorize vulnerabilities into broader topics based on their descriptions.
Functionality: Helps to classify vulnerabilities even when they do not match predefined keywords.

CVSS-Based Risk Prioritization:

Analyzes the severity of vulnerabilities using CVSS scores, prioritizing vulnerabilities based on their potential impact.
Functionality: Adjusts the level of security controls applied based on the vulnerability’s severity.

Automated Security Control Mapping:

Automatically maps vulnerabilities to NIST 800-53 controls, based on their characteristics and severity.
Functionality: Ensures compliance with best practices and regulatory requirements for vulnerability management.

Enhanced Controls for High-Risk Vulnerabilities:

For vulnerabilities that pose a significant risk (e.g., CVSS score above 9.0), the system assigns enhanced NIST controls.
Functionality: Provides additional protection for critical vulnerabilities.
