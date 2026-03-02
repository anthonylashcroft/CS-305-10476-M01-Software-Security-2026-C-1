# CS-305-10476-M01-Software-Security-2026-C-1
CS-305-10476-M01 Software Security 2026 C-1

## Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial was looking into assistance in securing their communications using data verfication with hashing functionality. I was tasked with developing a solution to this isssue by addressing any vulnerabilities their existing software had and dveloping a secure communication channel for their data transmissions.

## What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I feel that I properly selected the appropriate hashing algorithm to suit their needs. It was not the most robust, but weighing the pros and cons of each available option, this seemed to be the most appropriate. It is important to code securely, because any vulnerabilty in code can be exploited to steal sensitive customer or company data. Software security provides confindence to the client that the company can be trusted to handle their data. This improves the company's repuation.

## Which part of the vulnerability assessment was challenging or helpful to you?
The most challinging part of the vulnerability assesment for me was trying to find which vulnerabilites were applicable for the application that was being analyzed.

## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
By adding secure communication through Spring Boot API, a layer of security was added between user and server. This was futher layered by creating a certificate that not only provides confirmation that the site is secure but allowed for HTTPS communication. Adding SHA-256 hash based cryptography added another layer of security to ensure that even if data were intercepted, it would not be decryptable.

## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
By running the maven depency check tool, it was possible to analyze any secruity vulnerabilities introduced by older dependencies. Updating these dependencies and running the check again help to diminish these vulnerabilities. Once the code was refactored, the dependancies were checked again and the project was then compiled. If there were no errors, then dvelopment was a success.

## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I used web based resources like stack exchange and google to research many of the needs for this class. I used the google search to find details about all of the cryptrogphay options available, the meanings of different terms. I used stack exchange to find answers to questions that I had. Normally, these were questions that had already been asked by other users.

## Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
From this assingment, I would show them the results of project 2. The refactored code and the dependency check results show that I have the capability of developing with mindset of secure applications.
