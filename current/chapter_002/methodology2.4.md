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

### 2.4 Determining the Scale of a Secure Source Code Review

The level of secure source code review will vary depending on the business or regulatory needs of the software, the
size of the software development organization writing the applications and the skills of the personnel. Similar to
other aspects of software development such as performance, scalability and maintainability, security is a measure of
maturity in an application. Security is one of the non-functional requirements that should be built into every serious
application or tool that is used for commercial or governmental purposes.

If the development environment consists of one person programming as a hobby and writing a program to track
their weekly shopping in visual basic (CMM level 1), it is unlikely that that programmer will use all of the advice
within this document to perform extensive levels of secure code review. On the other extreme, a large organization
with thousands of developers writing hundreds of applications will (if they wish to be successful) take security very
seriously, just like they would take performance and scalability seriously.
Not every development organization has the necessity, or resources, to follow and implement all of the topics in
this document, but all organizations should be able to begin to write their development processes in a way that
can accommodate the processes and technical advice most important to them. Those processes should then
be extensible to accommodate more of the secure code review considerations as the organization develops and
matures.

In a start-up consisting of 3 people in a darkened room, there will not be a ‘code review team’ to send the code to,
instead it’ll be the bloke in the corner who read a secure coding book once and now uses it to prop up his monitor.
In a medium sized company there might be 400 developers, some with security as an interest or specialty, however
the organizations processes might give the same amount of time to review a 3 line CSS change as it gives to a
redesign of the flagship products authentication code. Here the challenge is to increase the workforce’s secure
coding knowledge (in general) and improve the processes through things like threat modelling and secure code
review.

For some larger companies with many thousands of developers, the need for security in the S-SDLC is at its greatest,
but process efficiency has an impact on the bottom line. Take an example of a large company with 5,000 developers.
If a change is introduced to the process that results in each developer taking an extra 15 minutes a week to perform
a task, suddenly that’s 1,250 hours extra each week for the company as a whole This results in a need for an extra 30
full time developers each year just to stay on track (assuming a 40 hour week). The challenge here is to ensure the
security changes to the lifecycle are efficient and do not impede the developers from performing their task.

<section class='callout-mono left small'>
<h3>Skilling a Workforce for Secure Code Review</h3>
<p>
There seems to be a catch-22 with the following sentiment; as many code developers are not aware or skilled in
security, a company should implement peer secure code reviews amongst developers.
How does a workforce introduce the security skills to implement a secure code review methodology? Many
security maturity models (e.g. BSIMM or OpenSAMM) discuss the concept of a core security team, who are skilled
developers and skill security subject matter experts (SMEs). In the early days of a company rolling out a secure code review process, the security SMEs will be central in the higher risk reviews, using their experience and
knowledge to point out aspects of the code that could introduce risk.
</p>
<p>
As well as the core security team a further group of developers with an interest in security can act as team local
security SMEs, taking part in many secure code reviews. These satellites (as BSIMM calls them) will be guided by
the core security team on technical issues, and will help encourage secure coding.
</p>
<p>
Over time, an organization builds security knowledge within its core, and satellite teams, which in turns spreads
the security knowledge across all developers since most code reviews will have a security SME taking part.
</p>
<p>
The ‘on-the-job’ training this gives to all developers is very important. Whereas an organization can send their developers on training courses (classroom or CBT) which will introduce them to common security topics and create
awareness, no training course can be 100% relevant to a developer’s job. In the secure code review process, each
developer who submits their code will receive security related feedback that is entirely relevant to them, since
the review is of the code they produced.
</p>
</section>

It must be remembered though, no matter what size the organization, the reason to perform secure code review is to catch more bugs and catch them earlier in the S-SDLC. It is quicker to conduct a secure code review and find bugs that way, compared to finding the bugs in testing or in production. For the 5,000-person organization, how long will it take to find a bug in testing, investigate, re-code, re-review, re-release and re-test? What if the code goes to production where project management and support will get involved in tracking the issue and communicating with customers? Maybe 15 minutes a week will seem like a bargain.