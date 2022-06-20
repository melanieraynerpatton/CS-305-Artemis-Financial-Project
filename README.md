# CS-305-Artemis-Financial-Project
This repository was created as part of an assignment for a software security course.

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a financial consulting company who wanted to modernize its operations by implementing updated software security principles and algorithms. Specifically, a vulnerability assessment needed to be performed in order to evaluate their current security levels and vulnerabilities. 

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I performed the vulnerability check, documented all the known vulnerabilities associated with the software, and included a description of it in the report. Additionally, I checked the code itself for any underlying vulnerabilities that would not be caught in a vulnerability assessment, such as code that is at risk for injection attacks and other loopholes. It is important to ensure that a software’s code itself is secure. Poor coding practices cannot be fixed with a simple package update, and depending on the program’s complexity, it may result in other aspects of the code being changed in order to fix vulnerable code. Security breaches are a bad look for any company, and theft of sensitive information can cause the public to lose their trust in you. Additionally, a company may face hefty fines if it is proven that their security breach was due to negligence. Losing business and paying large sums of money as consequences for a security breach are enough to put even the largest of corporations out of business. 

What about the process of working through the vulnerability assessment did you find challenging or helpful?

I found it challenging to document all the vulnerabilities found within the software. As seen in the report, there were quite a few vulnerabilities that needed to be documented. Most of the flaws are due to many different packages being out of date, so at least these issues are easily mitigated. 

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

In order to increase security for Artemis Financial, I researched how to fix their vulnerabilities and determined the changes that needed to be made to their code to make it more secure. In the future, I would look into alternative packages and tools that could be used in place of a particularly vulnerable or out of date package. Finding a more secure alternative is sometimes the better path to take, as opposed to just updating a package to its current version, especially if the most current version has problems of its own. 

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

I ensured the code and software application were functional and secure by refactoring the code in an appropriate manner. I changed the instances that would have left the program vulnerable to injection and I noted the updates that needed to be performed for each package and tool that contained security vulnerabilities. After refactoring the code, ensuring that no new vulnerabilities were introduced was as simple as running another dependency check. 

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

The most useful resource I employed in this assignment that I can see being useful in future programs as well is the Maven dependency check. It was quick and easy to implement, and it provided all the information I needed to determine the safety of the program as far as the packages and tools associated with it were concerned. Additionally, it saved me a lot of time researching the vulnerabilities due to its connection to the NIST. A great feature of the dependency check was its hyperlinks to the NIST that gave detailed information on the vulnerabilities listed in the report. These descriptions included information regarding how to mitigate the vulnerabilities, which was very helpful and saved a lot of time.

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

I would use this assignment to demonstrate that I have experience with software security and finding vulnerabilities present within the current packages and tools associated with the program. In particular, I know how to use a vulnerability scanning tool and I know how to use the information provided by it. 

