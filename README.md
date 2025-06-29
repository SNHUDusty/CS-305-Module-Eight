# CS-305-Module-Eight

1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

- Artemis Financial specializes in creating tailored financial plans covering savings, retirement, investments, and insurance. Since they manage sensitive personal and financial information—like Social Security numbers and tax documents—they required assistance to enhance the security of their web application. Their objective was to detect and address possible software vulnerabilities to protect the confidentiality, integrity, and accessibility of client data.

2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

- I performed both manual code review and static dependency analysis to identify vulnerabilities such as missing input validation, authentication and authorization gaps, insecure error handling, and outdated third-party libraries with known CVEs. Secure coding is essential as it safeguards user data, mitigates legal and financial risks, and sustains client trust. Additionally, software security enhances long-term value by ensuring regulatory compliance, reducing downtime, and protecting intellectual property.

3. Which part of the vulnerability assessment was challenging or helpful to you?

- Using the OWASP Dependency-Check tool was both challenging and highly beneficial. It demanded meticulous effort to match each CVE with the correct dependency and identify the proper remediation steps. Despite the difficulty, it streamlined the process of detecting third-party risks that could be missed in manual reviews.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

- I enhanced the security measures by adding input validation, ensuring proper authentication and authorization, standardizing error handling, and implementing logging along with rate limiting. Additionally, I replaced old, vulnerable dependencies with secure alternatives. Moving forward, I plan to keep utilizing tools such as OWASP Dependency-Check and static code analyzers like SonarQube, while also conducting regular threat modeling to identify and prioritize mitigation strategies based on their potential impact and ease of exploitation.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

- After implementing security enhancements, I verified functionality by testing each endpoint to ensure expected behavior and correct error responses. To ensure no new vulnerabilities arose, I reran the dependency-check tool and conducted another manual code review, concentrating on the changes and possible side effects from the updates. Additionally, I examined logs and tested authentication enforcement.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

- Helpful tools included OWASP Dependency-Check for static vulnerability analysis and secure coding guidelines from OWASP and vendor documentation. I also adhered to principles such as least privilege, input/output sanitization, and consistent exception handling—practices that are broadly applicable to almost any future software project.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

- I would demonstrate my ability to perform comprehensive vulnerability assessments, document and address risks, and implement secure coding practices in practical scenarios. I could share annotated code examples illustrating security improvements, my written mitigation strategy, and screenshots or logs from the dependency-check tool as proof of adherence to security standards.
