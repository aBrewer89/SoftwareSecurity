Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
   The client was Artemis Financial, a financial services company seeking to modernize its software while maintaining strict security standards.
   The issue they wanted us to address was the company's need to protect its financial data transmissions by implementing a secure web application 
   that uses cryptography to verify data integrity and prevent unauthorized access or tampering.

What did you do well when you found your client’s software security vulnerabilities?
   I successfully mapped potential attack vectors and pinpointing outdated cryptographic algorithms, using automated scanning tools, 
   which allowed for an efficient, comprehensive discovery phase.
   
Why is it important to code securely? 
   Writing secure code stops vulnerabilities before they are compiled. 
   It prevents costly data breaches, unauthorized data manipulation, and malicious injections.
   
What value does software security add to a company’s overall well-being?
   Software security protects brand reputation, ensures regulatory compliance, and preserves consumer trust, 
   directly preventing financial loss from legal penalties or remediation costs.

Which part of the vulnerability assessment was challenging or helpful to you?
   Generating dependency trees to see nested vulnerabilities was helpful.
   Eliminating false positives from the automated vulnerability assessment report without disrupting legacy business logic was challenging.

How did you increase layers of security?
   I implemented defense-in-depth by upgrading to strong cryptographic algorithms, enforcing HTTPS/TLS protocols, and establishing strict input validation rules.
   
How did you make certain the code and software application were functional and secure?
   I ensured functionality and security by using Regression Testing and SAST. 

After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
   I checked post-refactoring vulnerabilities by running automated dependency checks and comparing pre- and post-refactoring vulnerability scan baselines.

In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
   I will use Continuous Integration security scanning pipelines, strict adherence to the OWASP Top 10 guidelines, 
   and the practice of least privilege during code refactoring.
   
What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
   I will leverage automated SAST/DAST tools alongside the NIST NVD to prioritize mitigation strategies based on CVSS scores.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience.
What might you show future employers from this assignment?
   I would present the vulnerability assessment report and the refactored cryptographic code, with any sensitive business details redacted.
   This demonstrates hands-on experience in threat modeling, secure remediation, and verifying software integrity.
