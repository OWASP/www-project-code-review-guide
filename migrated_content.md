---

layout: col-sidebar
title: OWASP Code Review Guide
tags: example-tag
level: 0
type: documentation

---
<div style="width:100%;height:90px;border:0,margin:0;overflow: hidden;">

![_lab_big.jpg](_lab_big.jpg "_lab_big.jpg")

</div>

<div style="border:0,margin:0;overflow: hidden;">

<div style="margin: 5px; padding: 5px; float: left; width:70%">

</div>

</div>

# Code Review Guide

<table>
<tbody>
<tr class="odd">
<p>Please forward to all the developers and development teams you know</p></td>
<td><p>We would like to immediately start raising awareness about this OWASP resource. We plan to release the final version in Aug. 2017 after a public comment period ending July 31, 2017.</p>
<p>Thank you, Larry Conklin, Gary Robinson OWASP Code Review Guides Co-Leaders</p>
<p>Thank you, Larry Conklin, Gary Robinson OWASP Code Review Guides Co-Leaders</p>
<h2 id="introduction">Introduction</h2>
<h2 id="introduction">Introduction</h2>
<p>OWASP Code Review Guide is a technical book written for those responsible for code reviews (management, developers, security professionals). The primarily focus of this book has been divided into two main sections. Section one is why and how of code reviews and sections two is devoted to what vulnerabilities need to be to look for during a manual code review. While security scanners are improving every day the need for manual security code reviews still needs to have a prominent place in organizations SDLC (Secure development life cycle) that desires good secure code in production.</p>
<p>OWASP Code Review Guide is a technical book written for those responsible for code reviews (management, developers, security professionals). The primarily focus of this book has been divided into two main sections. Section one is why and how of code reviews and sections two is devoted to what vulnerabilities need to be to look for during a manual code review. While security scanners are improving every day the need for manual security code reviews still needs to have a prominent place in organizations SDLC (Secure development life cycle) that desires good secure code in production.</p>
<p>Second sections deals with vulnerabilities. It is based on the poplar OWASP 2013 top 10. Here you will find most of the code examples for both on what not to do and on what to do. A word of caution on code examples; Perl is famous for its saying that there are 10,000 ways to do one thing. The same is true for C#, PHP and Java or any other computer language. Now add in "Object-Oriented Programming" and if we are using design patterns or even what designs patterns are being used and sample code becomes very “iff” in what to write. We tried to keep the sample code so code reviews can see red flags and not “do it my way or else”.</p>
<p>Second sections deals with vulnerabilities. It is based on the poplar OWASP 2013 top 10. Here you will find most of the code examples for both on what not to do and on what to do. A word of caution on code examples; Perl is famous for its saying that there are 10,000 ways to do one thing. The same is true for C#, PHP and Java or any other computer language. Now add in "Object-Oriented Programming" and if we are using design patterns or even what designs patterns are being used and sample code becomes very “iff” in what to write. We tried to keep the sample code so code reviews can see red flags and not “do it my way or else”.</p>
<p>The last section is the appendix. Here we have content like code reviewer check list, etc. of items that really don’t flow in book form but needed to be included to make the code review guide compete.</p>
<p>The last section is the appendix. Here we have content like code reviewer check list, etc. of items that really don’t flow in book form but needed to be included to make the code review guide compete.</p>
<h2 id="review_of_code_review_guide_2.0">Review of Code Review Guide 2.0</h2>
<h2 id="review_of_code_review_guide_2.0">Review of Code Review Guide 2.0</h2>
<p>Constructive comments on this OWASP Code Review Release Candidate should be forwarded via email to owasp-codereview-project@owasp.org. Private comments may be sent to larry.conklin@owasp.org or gary.robinson@owasp.org . All comments are welcome. All comments should indicate the specific relevant page and section.</p>
<p>Constructive comments on this OWASP Code Review Release Candidate should be forwarded via email to owasp-codereview-project@owasp.org. Private comments may be sent to larry.conklin@owasp.org or gary.robinson@owasp.org . All comments are welcome. All comments should indicate the specific relevant page and section.</p>
<p>All feedback is critical to the continued success of the OWASP Code Review Guide.</p>
<p>All feedback is critical to the continued success of the OWASP Code Review Guide.</p>
<h2 id="licensing">Licensing</h2>
<h2 id="licensing">Licensing</h2>
<p>OWASP Code Review Guide is free to use. It is licensed under the <a href="http://creativecommons.org/licenses/by-sa/3.0/">http://creativecommons.org/licenses/by-sa/3.0/</a> Creative Commons Attribution-ShareAlike 3.0 license], so you can copy, distribute and transmit the work, and you can adapt it, and use it commercially, but all provided that you attribute the work and if you alter, transform, or build upon this work, you may distribute the resulting work only under the same or similar license to this one.</p></td>
<p>OWASP Code Review Guide is free to use. It is licensed under the <a href="http://creativecommons.org/licenses/by-sa/3.0/">http://creativecommons.org/licenses/by-sa/3.0/</a> Creative Commons Attribution-ShareAlike 3.0 license], so you can copy, distribute and transmit the work, and you can adapt it, and use it commercially, but all provided that you attribute the work and if you alter, transform, or build upon this work, you may distribute the resulting work only under the same or similar license to this one.</p></td>
<ul>
<li>Larry Conklin <a href="mailto:larry.conklin@owasp.org">1</a></li>
<li>Gary Robinson <a href="mailto:gary.robinson@owasp.org">2</a></li>
</ul>
<h2 id="project_email">Project Email</h2>
<ul>
<li>Project Email <a href="mailto:owasp-codereview-project@owasp.org">3</a></li>
</ul>
<h2 id="classifications">Classifications</h2>
<figure>
<img src="Owasp-defenders-small.png" title="Owasp-defenders-small.png" alt="Owasp-defenders-small.png" /><figcaption>Owasp-defenders-small.png</figcaption>
</figure>
<figure>
<img src="Cc-button-y-sa-small.png" title="Cc-button-y-sa-small.png" alt="Cc-button-y-sa-small.png" /><figcaption>Cc-button-y-sa-small.png</figcaption>
</figure>
<figure>
<img src="Project_Type_Files_DOC.jpg" title="Project_Type_Files_DOC.jpg" alt="Project_Type_Files_DOC.jpg" /><figcaption>Project_Type_Files_DOC.jpg</figcaption>
</figure>
<h2 id="related_projects">Related Projects</h2>
<p>OWASP Testing Guide <a href="https://www.owasp.org/index.php/OWASP_Testing_Project">4</a></p></td>
<ul>
<li><a href="/www-pdf-archive/File:OWASP_Code_Review_Guide_v2.pdf">Code Review Guide 2.0</a></li>
</ul>
<h2 id="in_print">In Print</h2>
<p>Code Review Guide 2.0 will be available in Lulu in the near future.</p>
<p><a href="http://www.lulu.com/content/5678680">Code Review Guide V1.1</a> on Lulu.</p></td>
</tr>
</tbody>
</table>

# Acknowledgements

The OWASP Code Review project was conceived by Eoin Keary, the OWASP
Dublin Founder and Chapter Lead.

`Code Review Mailing list`[`5`](mailto:owasp-codereview-project@owasp.org)

`Project leaders `<larry.conklin@owasp.org>` or `<gary.robinson@owasp.org>

__NOTOC__ <headertabs />

[Category:OWASP Project](Category:OWASP_Project )
[Category:OWASP_Defenders](Category:OWASP_Defenders )
[Category:OWASP_Document](Category:OWASP_Document )
