# Software-security-
Artemis Financial Practices for Secure Software Report
For this portfolio artifact, I selected my Project Two Practices for Secure Software Report. This project allowed me to demonstrate my understanding of software security by identifying vulnerabilities, implementing security improvements, and testing a Java Spring Boot application.

Client and Software Requirements

Artemis Financial was a financial consulting company that needed to improve the security of its software application. The company wanted to protect sensitive financial information and ensure that data could be transmitted securely. My responsibility was to identify potential security concerns and implement improvements that would help protect the application and its users.

Identifying Vulnerabilities and the Importance of Secure Coding

One thing I did well was using OWASP Dependency-Check to identify vulnerabilities in the application's dependencies. This helped me understand that security issues can exist even when the application's code appears to function correctly. Secure coding is important because it helps prevent unauthorized access, protects sensitive information, and reduces the risk of data breaches. For a financial company, maintaining strong software security also helps build customer trust and protects its reputation.

Challenges and Lessons Learned

One of the more challenging parts of this project was configuring the SSL certificate and getting the application to run correctly over HTTPS. I had to work through the keystore configuration, certificate settings, and application properties before everything worked. Although this took additional troubleshooting, it helped me better understand how certificates and secure communications work in real applications. Running the dependency scan was also helpful because it showed me how many security risks can come from third-party libraries.

Increasing Security and Future Vulnerability Assessments

I improved the application's security by implementing SHA-256 checksum generation, enabling HTTPS on port 8443, and configuring a self-signed certificate through a PKCS12 keystore. I also replaced the plaintext keystore password in the configuration file with an environment variable. These changes added protection for data integrity, communication security, and credential handling.

In future projects, I would continue using OWASP Dependency-Check along with code reviews, vulnerability databases, and security testing tools. I would prioritize vulnerabilities based on severity, exploitability, and potential business impact before selecting the appropriate mitigation techniques.

Functional Testing and Security Verification

After refactoring the application, I used Maven to run automated tests and confirmed that the project completed with BUILD SUCCESS, one test executed, and no failures or errors. I also opened the application's HTTPS endpoint in a browser to verify that the SHA-256 checksum was generated correctly.

I ran OWASP Dependency-Check to identify potential vulnerabilities in the project's dependencies. The scan reported 292 vulnerabilities across 16 vulnerable dependencies. Although the application functioned correctly, these findings showed that additional security improvements were still needed. This experience taught me that successful functional testing does not automatically mean an application is secure.

Helpful Tools and Coding Practices

Some of the most useful tools I worked with were Visual Studio Code, Java, Maven, Java keytool, and OWASP Dependency-Check. I also gained experience configuring Spring Boot applications, working with SSL/TLS certificates, using SHA-256 hashing, and managing application settings. These tools and practices will be useful in future software development projects because they provide a foundation for identifying security risks and building more secure applications.

Skills I Can Demonstrate to Future Employers

I would use this project to demonstrate my ability to analyze an existing application, identify security concerns, implement improvements, and verify that the software continues to function after changes are made. The completed report shows my experience with secure communications, checksum generation, certificate configuration, dependency scanning, and functional testing.

This project also demonstrates my troubleshooting and problem-solving skills. I was able to work through configuration issues, successfully run the application over HTTPS, and document both the improvements I completed and the vulnerabilities that still needed attention. These are skills I can continue building on as I move forward in the technology field.
