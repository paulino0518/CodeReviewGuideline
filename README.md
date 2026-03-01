# CodeReviewGuideline
A basic code review guideline so I don't review my code arbitrarily.  The purpose it to maintain and keep quality of code.  

#Conditionals
- Does every if(){} have an else{}? | Problem: Silent errors

#User input
DO NOT TRUST USER INPUT.  SANITIZE IT, VALIDATE IT, AND MAKE IT FIT EXACTLY WHAT YOU EXPECT.
- not empty,
- matching characters,
- handles spaces, and
- capitalizaiton
- default password and useranme to prevent timing attacks
- escaped
