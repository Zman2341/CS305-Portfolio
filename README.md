### CS305 Portfolio Reflection – Artemis Financial

**Client Summary**  
My client for this project was Artemis Financial, a company that helps people with financial planning and investment management. Their main issue was that their web application wasn’t secure enough to protect sensitive client and financial information. My goal was to find security problems in their system and update the code and dependencies to make it safer.

**Finding and Fixing Vulnerabilities**  
What I did well was carefully going through the code to find security weaknesses. I used OWASP Dependency-Check to look for vulnerable libraries and did a manual review to find issues like missing authentication, outdated encryption, and risky input handling. It felt rewarding to fix these problems and see how much more secure the application became.

**Why Secure Coding Matters**  
Coding securely is about more than just preventing hacks—it’s about protecting people’s trust and data. For a financial company, even one breach could cause a lot of damage. Writing secure code helps the company stay reliable, safe, and respected by its clients.

**Challenges and Helpful Steps**  
The hardest part was dealing with all the outdated dependencies and making sure updates didn’t break the application. The vulnerability assessment diagram from the course was really helpful because it gave me a clear process to follow step by step.

**Adding Layers of Security**  
I added several layers of security using a defense-in-depth approach. I enforced HTTPS, added checksums for file verification, validated all input, and improved error handling. If I do this again, I’d use tools like OWASP Dependency-Check, SonarQube, and Snyk to keep finding and fixing vulnerabilities faster.

**Testing and Functionality**  
After updating the code, I ran the application to make sure everything still worked properly. I tested the security changes and reviewed the code again to make sure I didn’t create new issues during refactoring.

**Helpful Tools and Practices**  
Throughout the project, I used GitHub for version control, OWASP Dependency-Check for scanning vulnerabilities, and Maven for managing dependencies. I also practiced good habits like avoiding hard-coded data, validating user input, and encrypting sensitive information. These will definitely help me in future projects.

**What I’d Show Employers**  
For future employers, I’d show the secure Artemis Financial project in my GitHub portfolio. It’s a good example of my ability to spot security risks, fix them, and follow best practices in real-world software development.
