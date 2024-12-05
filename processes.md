## Process

1. Application Overview & Risk Assessment
    - Who uses it
    - Purpose of the application
    - What roles are in the system
    - Concerns
    - Architecture
    - Internal vs Externally facing
    - How sensative the data is
    - Biggest risk data
    - Brainstorm risks
    
    Check
    - Readmes
    - Documentation
    - Tickets/Stories
    - Packages
    - Frameworks

2. Information Gathering
    - Identify attack vectors
    - Identify routes
    - Identify important functions
        - Cryptographic
        - Database integrations
        - Security boundaries
        - Authentication
        - Authorization
        - Dangerous functionality
        - Complex Logic
        - Custom protocols

4. Checklist Creation
    - Check github for ones that fit your need closest
    - https://github.com/0xRadi/OWASP-Web-Checklist
    - https://github.com/RedHatInsights/secure-coding-checklist

5. Perform Review
    - take notes
    - circle k
    - sources/sinks
    - pull requests tied to critical areas
    - unit tests

6. Report
    - Description
    - Location (files, line numbers)
    - Risk
    - Ease of exploitation
    - Likelyhood of exploitation
    - Remediation Guidance
    - Story