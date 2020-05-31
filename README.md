# IS893: Advanced Software Security

## Logistics
- Instructor: [Kihong Heo](https://kihongheo.kaist.ac.kr) (kihong.heo@kaist.ac.kr)
- TAs: 
- Time: 
- Office hour: 
- Location: 

## Course Description
This course covers advanced topics in software security. Students will be exposed to
techniques that are gaining increasing attention in the software security research
communities through research papers and programming assignments. Students will have
opportunities to develop their scientific communication skills through writing their
own project proposals and presenting their solutions.

## Grading

## Textbook
- Lecture slides will be provided

## Homework
This course includes programming assignments through which students will learn how to design
and implement program analyzers.
We will use Github/Github Classroom to provide skeleton code and manage submissions.
Make sure you have a Github account and get the [student developer pack benefits](https://education.github.com/pack).
Moreover, student should get familiar with `git`.
If you are new to `git`, see this [book](https://git-scm.com/book/en/v2).
Students will use the [OCaml](https://ocaml.org) programming language for the assignments.

- [Commercial Users of Functional Programming](http://cufp.org/2017)
- [OCaml for the Masses](https://queue.acm.org/detail.cfm?id=2038036)
- [Why OCaml](https://blog.janestreet.com/why-ocaml/)
- [Why Functional Programming Matters](https://dl.acm.org/doi/10.1093/comjnl/32.2.98) [<img src="youtube_social_icon_red.png" width="16" />](https://youtu.be/1qBHf8DrWR8)
- [Functional Programming in 40 minutes](https://youtu.be/0if71HOyVjY)

All submissions will be managed using Github.
For each assignment, a unique invitation URL for Github Classroom will be posted at [KLMS](http://klms.kaist.ac.kr).
Once you accept the invitation, a private repository for your assignment will be created.
You can push as many commits as you want before the deadline. We will grade the final commit of your `master` branch.

The late homework policy is as follows:
- 80% credit for one day late
- 50% credit for two days late
- NO credit given after two days late

## Academic Integrity Violation
Students who violates academic integrity will get an F.

## Schedule (tentative)
|#|Topics|Reading|Homework|
|-|------|-------|--------|
|1|Introduction||
|2|Concepts in Software Security||
|3|Runtime Monitoring|[[AddressSanitizer/USENIXATC12](https://www.usenix.org/system/files/conference/atc12/atc12-final39.pdf)], [[SoftBound/PLDI09](https://dl.acm.org/doi/abs/10.1145/1542476.1542504)]|
|4|Fuzzing||
|5|Differential Testing|[[DeepXplore/SOSP17](https://dl.acm.org/doi/10.1145/3132747.3132785)], [[NEZHA/S&P17](https://ieeexplore.ieee.org/abstract/document/7958601)]||
|6|Statistical Debugging||
|7|Delta Debugging||
|8|Static Analysis|[[Astree/PLDI03](https://dl.acm.org/doi/abs/10.1145/781131.781153)]|
|9|Type Systems|[[CCured/TOPLAS05](https://dl.acm.org/doi/10.1145/1065887.1065892)], [[TypeEq/CCS17](https://dl.acm.org/doi/abs/10.1145/3133956.3133998)]|
|10|Constraint-based Analysis|[[Securify/CCS18](https://dl.acm.org/doi/10.1145/3243734.3243780)], [[Ethainter/PLDI20](https://yanniss.github.io/ethainter-pldi20-draft.pdf)]|
|11|Symbolic Execution|[[Dart/PLDI05](https://dl.acm.org/doi/abs/10.1145/1065010.1065036)]|
|12|Assertion Checking|[[VeriSmart/S&P20](http://prl.korea.ac.kr/~pronto/home/papers/snp20.pdf)]|
|13|Project Presentation||
|14|Final Exam||
||[[CFI/CCS05](https://dl.acm.org/doi/10.1145/1102120.1102165)]
