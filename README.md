# Secure-Coding

**English:**
Secure Coding means writing software code in such a way that it prevents vulnerabilities and security risks (like SQL Injection, XSS, Buffer Overflow). The idea is: build security from the start, not patch later.

**Urdu:**
Secure coding ka matlab hai aisa code likhna jo hacking aur vulnerabilities se bacha rahe. Matlab development ke time hi security ka dhyan rakhna, na ke baad me patch karna.

### Secure Coding Practices (Best Practices)

**English:**

**Input Validation & Sanitization** – Never trust user input (avoid SQL Injection, XSS).

**Least Privilege Principle** – Code should run with minimum required permissions.

**Proper Error Handling** – Don’t expose system info in error messages.

**Authentication & Session Security** – Use strong password policies, MFA, session timeouts.

**Data Encryption** – Sensitive data (at rest + in transit) must be encrypted (AES, TLS).

**Code Reviews & Peer Testing** – Detect vulnerabilities early.

**Dependency Checking** – Don’t use outdated or vulnerable libraries.

**Logging & Monitoring** – Secure logging for incident response.

**Secure Defaults** – Default settings should be restrictive, not open.

**Patch Regularly** – Apply security updates to code and frameworks.

**Urdu:**
Secure coding practices me aata hai:

User input hamesha validate karo (SQL injection se bachne k liye).

Code minimum permissions k sath run karo.

Errors me system info na dikhayein.

Strong authentication aur session control use karo.

Data ko encrypt karo (AES, TLS).

Code review aur testing karo.

Old libraries avoid karo.

Secure logging rakho.

Default settings secure rakho.

Updates aur patches time pe lagao.

## Secure Coding Standards

**English:**
Standards are official guidelines/frameworks that define how to write secure code.

**OWASP Secure Coding Practices** – Covers top vulnerabilities (OWASP Top 10).

**CERT Secure Coding Standards** – Language-specific rules (C, C++, Java, etc.).

**ISO/IEC 27034** – International standard for secure application development.

**MISRA C/C++** – Secure coding rules for embedded/automotive systems.

**NIST SP 800-53 / 800-218 (SSDF)** – US security standards for coding & DevSecOps.

**Urdu:**
Secure coding standards wo official rules aur guidelines hain jo developers follow karte hain. Example:

OWASP practices → Web app security.

CERT standards → C, C++, Java secure rules.

ISO/IEC 27034 → Secure application ka framework.

MISRA C/C++ → Embedded systems ke liye.

NIST standards → Security + DevSecOps.

## Threat Modeling

**English:**
Threat Modeling is the process of identifying, analyzing, and prioritizing potential threats against an application before or during development. It helps developers design with security in mind.

#### Steps in Threat Modeling:

**Identify Assets** – What do we protect? (data, credentials, systems).

**Identify Threats** – Possible attacks (SQL Injection, DoS, insider abuse).

**Identify Vulnerabilities** – Weak points in code/design.

**Assess Risk** – Probability × Impact.

**Mitigation Plan** – Fix or reduce threats with controls.

**Urdu:**
Threat modeling ka matlab hai pehle se sochna ke app par kaunse threats aa sakte hain aur unse bachne ke liye kya karna hoga.

Steps:

Assets identify karo (kis cheez ko protect karna hai).

Threats list banao (attack types).

Vulnerabilities dekho (weak areas).

Risk assess karo (probability × damage).

Controls apply karo (fixes, patches, design changes).

### In short:

**Secure Coding** = Write code with security in mind.

**Best Practices** = Input validation, least privilege, encryption, patching.

**Standards** = OWASP, CERT, ISO/IEC, MISRA, NIST.

**Threat Modeling** = Identify + analyze + mitigate threats early in design.
