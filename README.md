# Common Application Vulnerability Types
# Broken Access Control:
This happens when users can access resources they shouldn't be allowed to access
Example: Normal Request GET /api/user/1001
Changed to: GET /api/user/1002
if it returns another user's data- IDOR vulnerability 
# Cryptographic Failures: 
Happens when sensitive data is not properly protected 
Example: http://company.com/login
Instead of : https://company.com/login
Attackers can intercept data
# Injection
This Occurs when attackers inject malicious code into inputs i.e SQL injection , Command Injection
Example SQL Injection: ' OR 1=1 --
# Insecure Design
When the application is poorly designed from the start
Example: A banking app that allows unlimited password attempts
Attackers can perform Brute force attacks 
# Vulnerable and Outdated components 
Using old software librabries 
Example: Old server versions, Outdated frameworks
# Identification and Authentification Failures 
This is the use of weak login systems
Example: no MFA , session ID exposed
# Security Logging and Monitoring Failures 
When systems do not detect attacks
Example: Login attempts not logged , Intrusion detection missing
Attackers can stay in the system for months
# Server-Side Request Forgery
This occurs when attackers trick the server into making internal requests
Example: Normal Request https://company.com/fetch?url=https://images.com/pic.jpg
SSRF Attack: An attacker changes the URL to access internal resources
https://company.com/fetch?url=https://localhost/admin


