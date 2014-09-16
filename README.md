deliverable_1
=============

####Edward Misback and Robbie McKinstry

The Project
-----------

We decided to test a subset of the functionality of the Think Through Math 
website, http://www.thinkthroughmath.com/. In particular, we chose to test the 
"Join The Movement"/"Request a Demo" form at 
http://www.thinkthroughmath.com/request-a-demo/. Because the chosen page is a 
webform, security is an important consideration: a poorly-designed form may 
allow attackers to execute injected code on the server. Usability is a further 
concern: an unwieldy user interface may prevent users from requesting a demo. 
In our tests, we focus on addressing these issues.

The Nonfunctional Requirements
------------------------------

Our nonfunctional requirements begin by addressing two specific security
concerns--cross-site scripting attacks and SQL injection. The specificity of 
these requirements helps to guide the implementation of tests of the site's 
overall security.

The other two nonfunctional requirements bring attention to potential user 
errors, again through a focus on particulars. Nonfunctional requirement 3 
requires that the page exhibits idempotence, so that accidental duplications 
in the database do not occur as a result of user errors. The final requirement 
seeks to ensure that a large majority of users can detect when they have made 
an error, so that the error may be corrected.

######For Bill Laboon's Software Testing class
