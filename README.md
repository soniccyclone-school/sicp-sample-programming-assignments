# SICP Sample Programming Assignments

This repository serves as an archive of the Sample Programming Assignments from the Structure and Interpretation of Computer Programs second edition's companion website.

Quality of life improvements have been performed by offering the sample code in scheme files instead of HTML; and PostScript files have been rendered to PDFs as well.

The README files within each directory are a markdown version of the original HTML page from the SICP site.

None of the content within this repository is my own. [All attribution goes to the original authors.](./LICENSE.md) My only work in this repository was in formatting the data to be more accessible by modern computers.

<br />

# Sample Programming Assignments

This selection of programming assignments, drawn from material developed for MIT's introductory computer science subject, is provided for the convenience of instructors teaching courses based on *Structure and Interpretation of Computer Programs*, and as a self-study aid for people using the book on their own.

There is a separate directory for each assignment. In general, individual directories will contain:

- The assignment in PostScript form (.ps) ready to be printed.
- The assignment source text, which you can modify and reprint. The source is designed to be processed by the LaTex text formatting system. In order to process the sources, you will need to download some [LaTeX support files](./Latex%20support%20files/README.md) from this site. In addition to the LaTeX text sources, some of the assignments require figures, which are included as graphics files.
- One or more files of source code (.scm) written in the Scheme dialect of Lisp. Most of the assignments involve modifying and extending such code.
- Answers to the problems are not included.

### Note to instructors

The PostScript files here are provided as a guide to what the problem sets should look like. You should not expect to simply print them out and assign them without modification. Some of the assignments available rely on specific features of MIT Scheme and idiosyncrasies our programming environment at MIT. Also, the exercise numbers alluded to in "the course notes" may not match the published textbook, since these assignments were constructed before the final revisions to the manuscript. In some cases (such as the adventure game) you will want to modify the problem set to remove MIT-isms and replace them with your own local color. Finally, the assignments are referred to by number -- problem set 1, problem set 2, etc. These numbers are the assignment numbers used during the semester that each one was assigned at MIT, and you will likely want to change them.

---

## Available assignments

|Assignment|Relevant sections in textbook|
|-|-|
|[Introductory assignment](./Introductory%20assignment/README.md)|1.1|
|[The game of twenty-one](./The%20game%20of%20twenty-one/README.md)|1.3|
|[Graphing with higher-order procedures](./Graphing%20with%20higher-order%20procedures/README.md)|1.3|
|[Continued fractions](./Continued%20fractions/README.md)|1.3|
|[RSA encryption](./RSA%20encryption/README.md)|1.2.6, 2.2.1|
|[Prisoner's dilemma](./Prisoners%20dilemma/README.md)|1.3, 2.2.1|
|[Picture language](./Picture%20language/README.md)|2.2.4|
|[Term-rewriting evaluator](./Term-rewriting%20evaluator/README.md)|1.1, 2.3|
|[Automated freshman advisor](./Freshman%20advisor/README.md)|2.3|
|[Generic Arithmetic](./Generic%20arithmetic/README.md)|2.4, 2.5|
|[Object-oriented adventure game](./Object-oriented%20adventure%20game/README.md)|3.1, 3.2, 3.3|
|[Concurrency](./Concurrency/README.md)|3.4|
|[Streams and series](./Streams%20and%20series/README.md)|3.5|
|[Evaluators](./Evaluators/README.md)|4.1, 4.2|
|[Languages for object-oriented progamming](./Languages%20for%20object-oriented%20programming/README.md)|4.1|
|[Register machines and compilation](./Register%20Machines%20and%20Compilation/README.md)|5.1, 5.2, 5.4, 5.5|