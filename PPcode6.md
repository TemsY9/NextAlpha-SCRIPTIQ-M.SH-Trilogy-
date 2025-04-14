Last Updated: April 2025
Service: SCRIPTIQ Citation Validator (API v1.0.1)

1. Overview
The SCRIPTIQ Citation Validator is a server-side service that analyzes academic text for citation formatting issues and attempts verification against academic databases such as CrossRef and PubMed. This Privacy Policy explains how we collect, process, and retain data sent through our API endpoints.

2. What Data We Collect
When you use the /validate_citations endpoint, the following data is temporarily received and processed:

Text content you submit (text_content)

Citation style provided by the user (e.g., APA, MLA, etc.)

Technical metadata (e.g., IP address, timestamp, and API key used) – for logging and monitoring

3. How We Use Your Data
We use your submitted data only to:

Extract and parse potential citations

Analyze citation formatting compliance

Check existence of citations in supported academic databases

Provide structured feedback and validation status

Data is processed in-memory and used exclusively for generating a response to your request.

4. Data Retention & Storage
We do not persistently store or log the full text content you submit for citation validation.

The following may be retained for up to 30 days for abuse detection and performance monitoring:

API key usage logs (with anonymized IPs)

Aggregated statistics (e.g., number of validations, average response time)

Non-identifiable error traces

Note: If you use a self-hosted or enterprise instance of this API, retention policies may differ and be configured locally.

5. Third-Party Services
We may query external academic databases (e.g., CrossRef, PubMed, Semantic Scholar) to verify citations. These services may log lookups or rate-limit access, but your full text is not sent—only extracted citation elements like title, DOI, author, or year.

We do not use third-party analytics or tracking systems within the API.

6. Security
All communication with our servers is encrypted via HTTPS. We implement the following additional security measures:

API Key authentication is enforced on all endpoints.

Rate limiting and abuse detection to prevent misuse.

Role-based access for backend infrastructure (zero public write access).

7. Your Rights
You have the right to:

Revoke your API key at any time

Inquire about temporary logs associated with your API usage

Request deletion of metadata (email us if required)

We are committed to GDPR-compliance and to protecting your academic content.

8. Contact Us
For any questions, suggestions, or concerns regarding your privacy:

📧 privacy@scriptiq.ai
🌐 https://scriptiq.ai/privacy
