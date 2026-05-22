# -OWASP-Juice-Shop-Web-Application-Security-Lab
 This repository/documentation contains my practical learning notes and hands-on exercises completed
while working with OWASP Juice Shop on TryHackMe. The lab provided exposure to real-world web application vulnerabilities commonly encountered during penetration testing and security assessments.

The objective of this exercise was to understand how modern web applications can be exploited due to insecure coding practices, improper input validation, weak authentication mechanisms, and security misconfigurations.

---

# Skills & Concepts Practiced

## Web Application Security Testing
- Authentication testing
- Session analysis
- Input validation testing
- Client-side security analysis
- Access control testing
- Forced browsing and hidden endpoint discovery

---

# Vulnerabilities Explored

## SQL Injection (SQLi)
Learned how improper sanitization of user-controlled input can lead to unauthorized database access and authentication bypasses.

### Key Learning Points
- Login bypass techniques
- UNION-based SQL Injection
- Error-based SQL Injection
- Input validation weaknesses
- Database enumeration concepts

---

## Cross-Site Scripting (XSS)
Performed both reflected and persistent XSS attacks within a controlled environment.

### Key Learning Points
- JavaScript payload injection
- HTML injection vectors
- Persistent XSS through stored user input
- Header-based XSS exploitation
- Client-side trust issues

### Example Attack Surface
- Search parameters
- Profile fields
- HTTP headers
- Login tracking systems

---

## Broken Authentication
Analyzed insecure authentication workflows and weak credential management practices.

### Key Learning Points
- Default credential risks
- Weak password policies
- Authentication bypass scenarios
- Session handling weaknesses

---

## Security Misconfiguration
Identified insecure application configurations that exposed sensitive functionality and hidden routes.

### Key Learning Points
- Directory enumeration
- Hidden endpoint discovery
- Exposed development resources
- Administrative interface exposure

---

## Sensitive Data Exposure
Observed how improperly protected information can leak sensitive operational details.

### Key Learning Points
- Publicly accessible files
- Information disclosure
- Error message leakage
- Metadata exposure

---

# Tools Used

## Primary Tools
- Burp Suite
- Browser Developer Tools
- OWASP Juice Shop
- TryHackMe Lab Environment

---

# Practical Activities Completed

- Intercepted and modified HTTP requests
- Manipulated custom headers
- Tested application input fields
- Enumerated hidden application routes
- Exploited persistent XSS vulnerabilities
- Performed authentication bypass exercises
- Analyzed client-server communication

---

# Key Takeaways

This lab reinforced the importance of:

- Proper input sanitization
- Secure authentication implementation
- Principle of least privilege
- Secure session management
- Server-side validation
- Security-focused application development

The exercises also improved my understanding of how attackers identify and exploit insecure web application behavior during real-world penetration testing engagements.

---

# Ethical Notice

All activities were performed inside authorized training environments designed for educational and defensive security purposes only.

---

# Continuous Learning

Currently expanding knowledge in:
- Web Application Penetration Testing
- API Security Testing
- Bug Bounty Hunting
- Secure Development Practices
- Network Security
- Threat Detection & Analysis

---

# Platforms
- TryHackMe
- OWASP Juice Shop

---

# Author
Pawan Yadav  
Cybersecurity Learner | Ethical Hacking Enthusiast | Web Security Focused
