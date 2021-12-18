# Methodology

## How can secure code review look like in your organization?

There is no one size fits all strategy for code reviews, neither is there a fool-proof recipe on how to handle and address security aspects during code reviews.  Instead, we have to take several considerations into account when designing an appropriate code review process for your organizations.

The most influential factors that define your process needs are:

- the size and maturity of the company
- the technology stack that is being used
- the type of product and it's associated risk levels

Still, there are a couple of best practices that evolved over the recent years. First of all, code reviews have evolve from an inspection-like activity that was performed only periodically, to a continuous way to collaborate and co-create software.  Similarly, security related considerations and investigations shifted from a periodical activity, to a more continuous effort that now encompasses also development teams. This development is also know as "Shift left". Shift left refers to the fact that security plays now a role sooner in the development process than ever before. This also means that software developers need to know about security. Code reviews are a perfect place to anker this new and added responsibility into the development life cycle. Still, developers need training and guidance on how to fulfill their new responsibility.   

Another aspect of this is that subject matter experts (SME) in the security field should be more tightly integrated. Also here, code reviews present an amazing opportunity. 

Have secure code reviews as part of the development process. Integrate SME with development teams. Have developers trained in secure coding principles.

## How rigorous should secure code review be and what are different levels of rigor (maturity)?

- Focusing on what matters by taking a risk based approach   

- Regulations and requirements for code review

  - Find out if compliance standards changed and if they now mention or require code review. If so, this information should be part of the code review guide. 

- Kind or of application, languages, frameworks, risk associated (customer? medical sector?)

- Technology Stack
  	- Framework & Language
   	- 3rd Party Components
   	- Datastore

- Information Gathering

  - Behavior Profiling


    -  Business Purpose


    -  Users (internal/external/roles)


    -  Information Sensitivity


    -  Documentation


    -  Mapping 


    -  Identify endpoints



  -  Risk assessment

- Info from 6.5. But updated/ changed. But nice to see methods of establishing/ assessing risks. This is more on a management/organization level

## When should a code review take place
A code review can take place at different point in time. Nowadays, most code reviews happen before the code is integrated in the main codebase (branch). This is often referred to "pre-checking"\footnote{For people familiar with the git versioning system that can be confusing.  Pre-checking code reviews, mean code reviews that happen before the code is merged into the main branch. Not that the code review happens before the code is committed to the branch.}

Another possibility is to do "post-checking" code reviews. In this case, the code reviews happen after the code is integrated with the main codebase. This can be handy if the changes are of low risk, and the development speed should be less impacted. 
Finally, code reviews can happen periodically and more in an audit style. This means that software developer develop larger pieces of work (or complete features) and the code is checked as a whole, instead of continuously. For security related code reviews this audit style is still widely used. 
