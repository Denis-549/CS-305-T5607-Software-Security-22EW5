# CS-305-T5607-Software-Security-22EW5
CS305 Projects
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a financial consulting firm that develops individualized financial plans for savings, retirement, investments, and insurance for their patrons. The client desires to modernize its operations and, as a crucial part of the success of its custom software, they want to implement and apply the most current and effective software security. Artemis Financial has a RESTful web application programming interface (API) and is seeking expertise in taking steps to protect the organization from external threats. Their goal also includes incorporating security measures that will ensure the transfer of information is secure, and with access control in place. 


What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I think having to do a code review, modification, then formulating a mitigation plan was particularly important, and rewarding in so many ways including ensuring all input is strictly validated in to the command input function. Successfully validating input would promote a secure system and prevent any injection attacks. This also include validation on API level, cryptography, client/server use of mutual certificate authentication, Certificate validation, Data Access (Username & Password), Code Review for Error (API layer code), and Encapsulation. Running dependency tests to view vulnerabilities was also a good practice. Secure coding helps to mitigate the vulnerabilities and risks associated with the software as well as it removes vulnerabilities that many exploits rely on. Software security for one ensures information is protected, it is also important for the software’s overall health (quick and smooth running of programs). The company’s assets and reputation is at risk of being tarnished or completely evaporated if a good software security measures are not implemented. 


What about the process of working through the vulnerability assessment did you find challenging or helpful?

I think the process overall was not as challenging, however what I found about the vulnerability assessment to be a bit challenging, was dealing with vulnerabilities that may not be “known” yet as well as identifying the false positives. In order to increase the layers of security I created an SSL certificate as well as making sure the project has HTTP posts. I think secure communication or making communication as safe as possible was quite helpful. 


How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

Being able to implement Input validation, RESTful API’s, Cryptography,  Client/Server use of certificates, Code Error (code review all command input functions as well as any API access layer code), as well as Encapsulation provided reasonable ways to implement security measures in order to ensure the code and software application were functional and secure. Refactoring the code, as well as running dependency checks helped to identify any new vulnerabilities. I think the afore mentioned areas of security and code review will be key in terms of assessing vulnerability and to determine mitigation techniques, it would be a good practice to add permissions or input validation, updating dependency check version to the latest version, Parsing of input, as well as suppressing false positives (vulnerabilities) on dependency check. 


How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

After refactoring the code, I used security libraries to deploy and implement the encryption algorithm cipher to the software application. I then verified the additional functionality with a checksum, after which I completed a secondary static testing of the refactored code using the dependency check tool to ensure code complies with software security enhancements. Then I completed the dependency check and reviewed the output to ensure I did not introduce additional security vulnerabilities.


What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

I think code review helped a lot, dependency checks did provide visibility when it comes to vulnerabilities and/or the ability to mitigate them. Additionally, Mutual Certificate Generation/Authentication, RESTful API, Encapsulation, Algorithm Ciphers, Static Testing, Checksum Verification, as well as doing Code Review and Mitigation will be helpful in the future.   


Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment, might you want to showcase to a future employer?

I think determining an appropriate encryption algorithm cipher to deploy given the security vulnerabilities, and justifying my reasoning was one area in which I think I did relatively well. One other assignment that I would like to highlight is my Vulnerability Assessment Report. Specifically my understanding of how to find and understand areas of security using the Vulnerability Assessment Process Flow Diagram, and then Identifying all vulnerabilities in the code base by manually inspecting the code, formulating a mitigation plan based on the client’s business needs and/or system architecture.
