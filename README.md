# Java-CS-305
Refactored Java Code for CS-305
Artemis Financial, a client specializing in financial services, required secure software solutions to protect sensitive data in transit and at rest. Their main concern was strengthening data encryption, hashing, and SSL/TLS configurations to mitigate potential breaches. In uncovering software security vulnerabilities, I methodically reviewed the code, replaced weak or deprecated algorithms (such as MD5 or SHA-1) with stronger options like SHA-256, and ensured the SSL keystore was configured properly—demonstrating the importance of coding securely to protect both client data and the company’s reputation. Secure coding practices add immense value by preventing costly data breaches, safeguarding customer trust, and enhancing long-term business stability. Although manually sifting through code to identify logical and syntactical flaws was at times tedious, this vulnerability assessment proved invaluable for recognizing outdated methods and dependencies that could expose the system to attacks. I added layers of security by integrating safer hashing algorithms, validating the keystore password and certificate, and employing static analysis tools like OWASP Dependency-Check to ensure no new vulnerabilities were introduced after refactoring. During functional tests and final scans, I confirmed that the application ran smoothly and that all critical security checks passed without introducing new flaws. To maintain this approach going forward, I would continue using static analysis tools and structured vulnerability assessments to prioritize risks, and I would regularly update dependencies to address newly discovered exploits. For future assignments, resources such as secure coding guidelines, cryptography best practices, and the use of automated scanners will be instrumental. In a professional setting, I could showcase both the refactored code and the documented vulnerability assessment process—from initial discovery to final testing—to demonstrate my ability to enhance software security effectively, thus highlighting my skills, knowledge, and hands-on experience to potential employers.
