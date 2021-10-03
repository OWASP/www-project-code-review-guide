---

layout: col-sidebar
title: OWASP Code Review Guide
tags: Code Review Guide
level: 3
type: documentation

---

[![OWASP Lab](https://img.shields.io/badge/owasp-lab-yellow.svg)](https://owasp.org/projects/#all-projects)
[![CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-sa/4.0/)

The current (July 2017) PDF version can be found [here](assets/OWASP_Code_Review_Guide_v2.pdf)

OWASP Code Review Guide is a technical book written for those responsible for code reviews (management, developers, security professionals). The primarily focus of this book has been divided into two main sections. Section one is the "why and how of code reviews" and section two focuses on the "types of vulnerabilities and how to identify throughout the review". While security scanners are improving every day the need for manual security code reviews still needs to have a prominent place in organizations' SDLC (Secure Development Life Cycle) that desires good secure code in production.

Chapters in the second section are mostly based on the popular OWASP 2013 top 10. Here you will find most of the code examples for both on "what not to do" and on "what to do". A word of caution on code examples; Perl is famous for its saying that there are 10,000 ways to do one thing. The same is true for C#, PHP, and Java or any other computer language. Now add in "Object-Oriented Programming" and if we are using design patterns or even what designs patterns are being used and sample code becomes very “iffy” in what to write. We tried to keep the sample code so code reviewers can see red flags and not “do it my way or else”.

The last section is the appendix. Here we have content like code reviewer check list, etc. of items that really don't flow in book form but needed to be included to make the code review guide complete. 

## Licensing

OWASP Code Review Guide is free to use. It is licensed under the [Creative Commons Attribution-ShareAlike 4.0 license](http://creativecommons.org/licenses/by-sa/4.0/), so you can copy, distribute and transmit the work, and you can adapt it, and use it commercially, but all provided that you attribute the work and if you alter, transform, or build upon this work, you may distribute the resulting work only under the same or similar license to this one.
