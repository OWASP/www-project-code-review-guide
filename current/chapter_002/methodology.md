---

title: Methodology
layout: col-document-adv
tags: Code Review Guide
document: OWASP Code Review Guide
author:
contributors:
order: 
altfooter: true

---

**Technical Reference For Secure Code Review** 

Here the guide drills down into common vulnerabilities and technical controls, including XSS, SQL injection,
session tracking, authentication, authorization, logging, and information leakage, giving code examples in
various languages to guide the reviewer.

This section can be used to learn the important aspects of the various controls, and as an on-the-job reference
when conducting secure code reviews.

We start with the OWASP Top 10 issues, describing technical aspects to consider for each of these issues. We
then move onto other common application security issues not specifc to the OWASP Top 10
Secure code review is probably the single-most efective technique for identifying security bugs early in the
system development lifecycle. When used together with automated and manual penetration testing, code
review can signifcantly increase the cost efectiveness of an application security verifcation efort.

This guide does not prescribe a process for performing a security code review. Rather, it provides guidance on
how the efort should be structured and executed. The guide also focuses on the mechanics of reviewing code
for certain vulnerabilities.

Manual secure code review provides insight into the “real risk” associated with insecure code. This contextual,
white-box approach is the single most important value. A human reviewer can understand the relevance of
a bug or vulnerability in code. Context requires human understanding of what is being assessed. With appropriate context we can make a serious risk estimate that accounts for both the likelihood of attack and the
business impact of a breach. Correct categorization of vulnerabilities helps with priority of remediation and
fxing the right things as opposed to wasting time fxing everything.
