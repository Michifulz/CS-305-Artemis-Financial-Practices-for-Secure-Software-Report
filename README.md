# CS-305-Artemis-Financial-Vulnerability-Assessment-Report

 	Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

The Client Artemis Financial is a financial consulting company, with the goal of modernizing its software. issues that were presented were an insecure system that needed to be updated and secured in order to have financial transactions.

 	What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I did well in identifying outdated dependencies and API interactions in the system. This is important because it can show areas that are vulnerable to attacks. 
It is important to code with security in mind  because by not doing so it puts the system at risk of a major attack, data loss, data leaks, etc. 
Such leaks can have effects on  private data, financial information, public image, and more. Because of all of these factors, it’s easy to see why having a secure system is so important to a company and their well-being,  security flaws cost money, time, and trust. 

 	What about the process of working through the vulnerability assessment did you found challenging or helpful?

Working through the vulnerability assessment was insightful for me. it helped me to think about things in a different light take a step back and look at the system in a few different ways. I think the most difficult part for me was going through the vulnerabilities and putting them in the assessment. 

 	How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

I included the SHA-256 hash function as well as attempting to update the dependencies. I also made sure to suppress all the false positives from the vulnerability report. This is because I didn’t want to try and add security measures for something that didn’t need them. 


 	How did you ensure the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

Firstly, before making any modifications I ran an OWASP dependency check. I then modified the code, ran the code, and ensured that the hash function worked. I also ran the code using the debug feature to ensure no bugs or errors were showing up. Finally, I did an OWASP dependency check, which I did to see if I had added any new vulnerabilities. 

 	What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

I found the OWASP dependency check to be helpful when finding out if dependencies are vulnerable. This is something I will use in future projects to help me ensure that I’m coding securely in that way.
Another thing I will be taking forward is the lessons I learned about secure coding practices. These are things I will be utilizing in my projects, future assignments, and careers going forward. 


	Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

if I were to present this assignment to a future employer, I’d love to showcase the work I did with the dependencies. Executing the OWASP dependency check and suppressing the false positives in order to give a clearer picture of what needs attention. 
