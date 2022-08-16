# Software-Security
# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a financial consulting company that aids their clientelle by creating individualized financial plans. They want to modernize their operations and implement the most updated and secure software security elements. I was tasked with adding file verification in the form of a checksum to the web application to ensure that the data is communicated securely. I was also required to perform dependency checks to ensure that all vulnerabilites were properly addressed. 
# What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I used static testing to identify any software security vulnerabilities. By using a maven dependency check, I was able to automatically view any vulnerabilities, most of which were able to be corrected by updating plugins. I also performed a manual review to check for any vulnerabilites which could've been missed by the dependency check. Practicing secure coding prevents any data theft from outside entities, protects the customer's private information, and protects the company reputation. The company will earn a good reputation by keeping their patrons sensitive information secure, which will in turn increase profit and clientelle. 
# What about the process of working through the vulnerability assessment did you find challenging or helpful?
The maven dependency check was very helpful because it quickly identified vulnerabilities that I could then click on and learn more information about. It was challenging to go through and figure out what was a false positive because there are so many vulnerabilities to manually look through.
# How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
It was important to implement multiple layers of security for our client because of how vital it is to protect their patrons' data. I used a secure network layer by ensuring that the web application made secure communications. I also used vulnerability programs such as the dependency check to check for vulnerabilities. I would continue to use these, as well as performing secondary and functional testing to determine mitigation techniques for each project. 
# How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
I ensured that the code and application was functional and secure by testing and executing the program. To ensure that the application was securte, I generated a self-signed certificate and deployed an algorithm cipher and checksum. Once the code was executed, I was able to pull up the application in my web browser to verify that the code deployed properly. I also performed a dependency check and a manula review to find any vulnerabilites that needed to be addressed. After refactoring my code, I had to complete a new dependency check to ensure that I did not introduce any new vulnerabilities. 
# What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
One resource that I found throuhgout my research in this class is a website called techtarget.com. I found that this website has a lot of valuable information which is very easy to understand. I utilized this website multiple times throughout this course. Implementing a maven dependency check is a tool which will be very beneficial in the future to identify possible security vulnerabilites. 
# Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
I would showcase my ability to deploy the algorithm cipher and checksum properly. I was able to write the code from scratch and access the data on a localhost webpage. 
