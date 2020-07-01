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

### 2.1 Why Does Code Have Vulnerabilities?

MITRE has catalogued circa 1000 diferent kinds of software weaknesses in the CWE project. These are all
diferent ways that software developers can make mistakes that lead to insecurity. Every one of these weaknesses is subtle and many are seriously tricky. Software developers are not taught about these weaknesses in
school and most do not receive any on the job training about these problems.
These problems have become so important in recent years because we continue to increase connectivity
and add technologies and protocols at an extremely fast rate. The ability to invent technology has seriously
outstripped the ability to secure it. Many of the technologies in use today simply have not received enough
(or any) security scrutiny.
There are many reasons why businesses are not spending the appropriate amount of time on security. Ultimately, these reasons stem from an underlying problem in the software market. Because software is essentially a black box, it is extremely difcult for a customer to tell the diference between good code and insecure
code. Without this visibility vendors are not encouraged to spend extra efort to produce secure code. Nevertheless, information security experts frequently get pushback when they advocate for security code review,
with the following (unjustifed) excuses for not putting more efort into security:
> We never get hacked (that I know of), we don’t need security.

> We have a firewall that protects our applications.

> We trust our employees not to attack our applications.

Over the last 10 years, the team involved with the OWASP Code Review Project has performed thousands of
application reviews, and found that every non-trivial application has had security vulnerabilities. If code has
not been reviewed for security holes, the likelihood that the application has problems is virtually 100%.
Still, there are many organizations that choose not to know about the security of their code. To them, consider
Rumsfeld’s cryptic explanation of what we actually know:

> ...we know, there are known knowns; there are things we know we know. We also know there are known unknowns; that is to say we know there are some things we do not know. But there are also unknown unknowns-- the ones we don’t know we don’t know.
> - Donald Rumsfeld

If informed decisions are being made based on a measurement of risk in the enterprise, which will be fully
supported. However, if risks are not being understood, the company is not being duly diligent, and is being
irresponsible both to shareholders and customers
