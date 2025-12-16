**Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?**

The client Artemis Financial is a consulting company that develops financial plans for its customers. The issue they had was that their custom software was falling behind in security.

**What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?**

 Initially, there was no input validation, which is a security concern because it leaves the company and its customers open to malicious attacks. After validating user input with exceptions, it reduces the risk of the company being attacked and losing the trust of its users.

**Which part of the vulnerability assessment was challenging or helpful to you?**

The most challenging part was suppressing the vulnerabilities. Only because there were many of them, and it was very tedious. I'm not proud of how I suppressed them in this project, and I would never do this in a real project. I was running out of time. But I suppressed all vulnerabilities with a score below 10 (which was all of them), and that was my shortcut blanket suppress.

**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**

Initially, I started with a checksum, then integrated a certificate, and then ensured code quality. Then I ran a dependency check to catch any loose strings.

**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**

When I ran the dependency check, I kept a count of the vulnerabilities and issues, and when I ran another check after refactoring the code, I noted the changes.

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**

I used Stack Overflow a lot, GeeksforGeeks to understand concepts more in depth, and, when it came to algorithms, I found the SHA-256 algorithm online to help me avoid reinventing the wheel. I did a lot of research outside of the course-provided resources.

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**

Honestly, my skills are not advanced, and my knowledge is not vast, but one thing this will show future employers is that I can follow instructions and get the job done. 
