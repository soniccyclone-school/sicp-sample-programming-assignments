# Freshman advisor

## Relevant sections in text: 2.3

This assignment, which provides experience with symbol manipulation, explores the possibility of replacing the college advising system with a rather stupid conversational program, based loosely on Joseph Weizenbaum's famous "Doctor" program of the 1960's. For this assignment, we provide a rule-based pattern matcher, so that the assignment serves as an introduction to rule-based programming as well as to symbol manipulation.

The pattern matcher here is quite sophisticated. It uses success and failure continuations to implement backtracking for segment variables (much in the style of the AMB evaluator of section 4.3). At this point in the course, we typically do not ask students to study the implementation of the pattern matcher, but only to use it as a black box, although we sometimes include a lecture on this material. We do not have explanatory notes for the matcher available, but you can find an explanation of a similar matcher in Abelson and Sussman, "Lisp: a Language for Stratified Design," Byte Magazine, February 1988.

|Files for download:||
|-|-|
|adv.tex|TeX source for the assignment.|
|adv.ps|Postscript file for printing the assignment|
|adv.scm<br />match.scm|Scheme source code required for this assignment.|

⬅[Return to sample assignment page](../README.md)