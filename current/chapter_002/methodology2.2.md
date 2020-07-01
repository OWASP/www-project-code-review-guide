---

title: Methodology (cont.)
layout: col-document-adv
tags: Code Review Guide
document: OWASP Code Review Guide
author:
contributors:
order: 
altfooter: true

---

### 2.2 What is Secure Code Review?

Code review aims to identify security flaws in the application related to its features and design, along with the
exact root causes. With the increasing complexity of applications and the advent of new technologies, the
traditional way of testing may fail to detect all the security faws present in the applications. One must understand the code of the application, external components, and configurations to have a better chance of finding the flaws. Such a deep dive into the application code also helps in determining exact mitigation techniques
that can be used to avert the security flaws.

It is the process of auditing the source code of an application to verify that the proper security and logical
controls are present, that they work as intended, and that they have been invoked in the right places. Code
review is a way of helping ensure that the application has been developed so as to be “self-defending” in its
given environment.

Secure code review allows a company to assure application developers are following secure development
techniques. A general rule of thumb is that a penetration test should not discover any additional application
vulnerabilities relating to the developed code after the application has undergone a proper security code
review. At the least very few issues should be discovered.

All security code reviews are a combination of human effort and technology support. At one end of the spectrum is an inexperienced person with a text editor. At the other end of the scale is an expert security team with advanced static analysis (SAST) tools. Unfortunately, it takes a fairly serious level of expertise to use the current
application security tools effectively. They also don’t understand dynamic data flow or business logic. SAST
tools are great for coverage and setting a minimum baseline.

Tools can be used to perform this task but they always need human verifcation. They do not understand
context, which is the keystone of security code review. Tools are good at assessing large amounts of code and
pointing out possible issues, but a person needs to verify every result to determine if it is a real issue, if it is
actually exploitable, and calculate the risk to the enterprise. Human reviewers are also necessary to fll in for
the significant blind spots, which automated tools, simply cannot check.
