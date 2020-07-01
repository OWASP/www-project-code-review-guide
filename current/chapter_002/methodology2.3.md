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

### 2.3 What is the diference between Code Review and Secure Code Review?

The Capability Maturity Model (CMM) is a widely recognized process model for measuring the development
processes of a software development organization. It ranges from ‘level 1’ where development processes are
ad hoc, unstable and not repeatable, to ‘level 5’ where the development processes are well organized, documented and continuously improving. It is assumed that a company’s development processes would start out at level 1 when starting out (a.k.a start-up mode) and will become more defined, repeatable and generally
professional as the organization matures and improves. Introducing the ability to perform code reviews (note
this is not dealing with secure code review yet) comes in when an organization has reached level 2 (Repeatable) or level 3 (Defined).

Secure Code Review is an enhancement to the standard code review practice where the structure of the review process places security considerations, such as company security standards, at the forefront of the decision-making. Many of these decisions will be explained in this document and attempt to ensure that the
review process can adequately cover security risks in the code base, for example ensuring high risk code is
reviewed in more depth, ensuring reviewers have the correct security context when reviewing the code, ensuring reviewers have the necessary skills and secure coding knowledge to effectively evaluate the code.
