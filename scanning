#Scanning

Target Website:
- Name: Example Site
- URL: testfire.net
- Scanning Date: 2024-08-12

#Scanning Tools and Methods
- Tools Used:
  - OWASP ZAP: Version 2.11.1, used for automated vulnerability scanning.
  - Nessus: Version 10.0.0, used for network vulnerability assessment.
  - Burp Suite: Version 2024.1, used for manual testing and scanning.

# Scanning Results

## Vulnerabilities Identified

###Vulnerability 1: SQL Injection
- Description: Input fields vulnerable to SQL injection, allowing potential database manipulation.
- Severity: High
- Location: "/login" page
- Impact: Potential unauthorized access to database records.
- Proof of Concept: Injected payload "' OR 1=1--" in the login page username field; returned all records.
- Recommendations: Sanitize and parameterize all SQL queries.

#### Vulnerability 2: Cross-Site Scripting (XSS)
- Description: Reflected XSS vulnerability in the search results page.
- Severity: Medium
- Location: `/search` page
- Impact: Attackers can execute scripts in users' browsers.
- Proof of Concept: Injected payload `<script>alert('XSS')</script>` in the `search` field; script executed.
- Recommendations: Escape and validate user inputs to prevent XSS.

Key Findings:
-SQL Injection vulnerabilities are critical and should be addressed immediately.
-Several instances of XSS were found, indicating a need for improved input validation.

## Recommendations
- Sanitize SQL Queries: Ensure all user inputs are sanitized and parameterized.
- Improve Input Validation: Implement strict validation and encoding to prevent XSS.
- Review Security Policies: Regularly review and update security policies and practices.


