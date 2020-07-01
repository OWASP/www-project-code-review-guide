---

title: How to Use the Code Review Guide
layout: col-document-adv
tags: Code Review Guide
document: OWASP Code Review Guide
author:
contributors:
order: 
altfooter: true

---

The contents and the structure of the book have been carefully designed. Further, all the contributed chapters have been judiciously edited and integrated into a unifying framework that provides uniformity in structure and style.

**This book is written to satisfy three diferent perspectives.**
1. Management teams who wish to understand the reasons of why code reviews are needed and why they are included in best
practices in developing secure enterprise software for todays organizations. Senior management should thoroughly read sections one and two of this book. Management needs to consider the following items if doing secure coding is going to be part of
the organizations software development lifecycle:
    * Does organization project estimation allot time for code reviews?
    * Does management have the capability to track the relevant metrics of code review and static analysis for each project and
    programmer?
    * Management needs to decide when in the project life cycle will that code reviews should be done in the project lifecycle and
    what changes to existing projects require review of previously completed code reviews.

2. Software leads who want to give manfully feedback to peers in code review with ample empirical artifacts as what to look for
in helping create secure enterprise software for their organizations. They should consider:
    * As a peer code reviewer, to use this book you frst decided on the type of code review do you want to accomplish. Lets spend a
few minutes going over each type of code review to help in deciding how this book can be assistance to you.
    * API/design code reviews. Use this book to understand how architecture designs can lead to security vulnerabilities. Also if the
API is a third party API what security controls are in place in the code to prevent security vulnerabilities.
    * Maintainability code reviews. These types of code reviews are more towards the organizations internal best coding practices.
This book does cover code metrics, which can help the code reviewer, better understand what code to look at for security vulnerabilities if a section of code is overly complex.
    * Integration code reviews. Again these types of code reviews are more towards the organizations internal coding policies. Is
the code being integrated into the project fully vetted by IT management and approved? Many security vulnerabilities are now
being implemented by using open source libraries whichh may bring in dependencies that are not secure.
    * Testing code reviews. Agile and Test Driven design where programmer creates unit tests to prove code methods works as the
programmer intended. This code is not a guide for testing software. The code reviewer may want to pay attention to unit test
cases to make sure all methods have appropriate exceptions; code fails in a safe way. If possible each security control in code has
the appropriate unit test cases.

3. Secure code reviewer who wants an updated guide on how secure code reviews are integrated in to the organizations secure
software development lifecycle. This book will also work as a reference guide for the code review as code is in the review process.
This book provides a complete source of information needed by the code reviewer. It should be read frst as a story about code
reviews and seconds as a desktop reference guide.