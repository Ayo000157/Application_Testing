# HTTP Request Interception and Modification using Burp Suite
# Objective: 
The objective of this exercise was to understand how HTTP requests are sent from a browser to a web server and how security testers can intercept and analyze these requests using Burp Suite.

# Tool used:
-Burp suite (Proxy and Intercept feature)
# Target:
-google.com
# Methodology: 
1.Configured Burp Suite as a proxy between the browser and the internet.
2.Enabled the "intercept" feature in Burp Suite
3.Sent a request to google.com from the browser.
4.Captured the HTTP request before it reached the server.
5.Observed and slightly modified parts of the request headers
6.Forwarded the modified request to the server to observe the response
# Findings:
-Burp suite successfully intercepted the HTTP request
-The request header and parameters could be viewed and modified before reaching the server
-This demonstrates how web security testers inspect web traffic to analyze how applications process requests.
# Security Insight:
Interception and Modification of HTTP requests is a fundamental technique used in Web Application Security Testing. It helps testers identify vulverabilities such as:
-Parameter manipulation
-Input Validation issues
-Authentification bypass attempts
