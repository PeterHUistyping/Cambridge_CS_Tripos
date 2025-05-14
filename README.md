# Computer Science Tripos

> *Reference:*

- [Cambridge Lecture Notes &amp; Example sheets](https://www.cst.cam.ac.uk/teaching)
- [Past Paper by Topics](./Past_Paper.html)
- Textbooks / Online ([Wiki](https://www.wikipedia.org/), [Open Course Ware](https://ocw.mit.edu/))
- [ExamTips](./Note/Tips.pdf)

<!--  [Supervision Reference](./Supervision_Reference.html) -->

## [Updated] Notes

- Category: ✎ summary; ✓ past paper; ■ extra notes
- Note that related Tripos courses > 1 is *cross-disciplinary* by nature.

### Math / AI

| id  | name                                                                          | coverage                                               | Tripos                                                            |
| --- | ----------------------------------------------------------------------------- | ------------------------------------------------------ | ----------------------------------------------------------------- |
| 1   | [Relations and Functions](./Note/Relation_Function.pdf)                          | def, properties and<br />relationship                  | IA Discrete Math ✎                                              |
| 1-2 | [Standard Random Variables](./Note/Standard%20Random%20Variables.pdf)            | Discrete/Continuous RV<br />Joint/marginal probability | IA Intro to Probability/NST Math<br />IB Data Science, etc ✎    |
| 1-3 | [Information Theory](./Note/InformationTheory.pdf)                               | Entropy, ML loss function                              | IB Formal model of language<br /> II InfoTheory                   |
| 1-4 | [Machine Learning](https://peterhuistyping.github.io/Machine_Learning_Guidance/) | Prob, Data Science, ML<br />Practical, Troubleshooting | IA Intro to Prob, MLRD<br />IB Data Science, AI<br />II MLBI, etc |

> *Reference:*

- Data Science
  - [Confidence Interval](./Ref/IBDataSci/Confidence%20intervals.pdf). Source: [@Dimitrios Los](https://dimitrioslos.com/supervisions/)

### Low-level (OS, Arch)

| id  | name                                                               | coverage                  | Tripos                                                                                                                                                 |
| --- | ------------------------------------------------------------------ | ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 2-1 | [Data Segment and Linking](./Note/Data%20Segment%20and%20Linking.pdf) | Memory and ABI            | IA Java - IB C/C++ (ProgLang)<br />IA OS - IB Arch (RISC) ✎<br />IB Compiler Construction ✓<br />IB Concurrent System                              |
| 2-2 | [Memory Address Calculation](./Note/Memory%20Calculation.pdf)         | Page table, TLB and cache | IA OS ✎<br />IB&II Computer Architecture<br />MSI+Cacheline ✓ Q [y21p5q3](https://www.cl.cam.ac.uk/teaching/exams/pastpapers/y2021p5q3.pdf) <br />i |
| 2-3 | [Comparative Architectures](./Note/Comparative%20Architectures.pdf)   | design tradeoff           | IB Arch & II Ad Arch ■<br />IB Compiler Construction                                                                                                 |

### Theories

| id  | name                                                                     | coverage                                       | Tripos                                                    |
| --- | ------------------------------------------------------------------------ | ---------------------------------------------- | --------------------------------------------------------- |
| 3-1 | [Concurrency Control](./Note/Concurrency%20Control.pdf)                     | for single object<br /> and transactions       | IB Architecture (Mem ACID)<br />IB Concurrent System  ✎ |
| 3-2 | [Clocks Broadcast Replication](./Note/Clocks%20Broadcast%20Replication.pdf) | causality, summary                            | IB Distributed, Network ✎✓                             |
| 3-3 | [Network by Analogy](./Note/Network%20by%20Analogy.pdf)                     | five-layer OSI                                | IB Computer Networking                                    |
| 3-4 | [HCI Principles](./Note/HCI.pdf)                                            | Heuristic Evaluation,<br />  Gestalt Cognitive | IA Interaction Design<br />IB Further HCI ✎             |

> *Reference:*

- Computer Networking
  - [Course work reference (2015)](https://github.com/danielchatfield/cst1b-computer-networking), credit: [@Daniel Chatfield](https://github.com/danielchatfield/)

#### Computation

Languages and Automata, Compiler, Algorithm and Complexity

| id  | name                                                              | coverage                                                                 | Tripos                                                                                                                                                                                        |
| --- | ----------------------------------------------------------------- | ------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 4-1 | [Formal Languages <br />and Automata](./Note/Formal%20Languages.pdf) | Chomsky hierarchy<br />RegLang ⇔ DFA<br />CFG ⇔ PDA<br />CSG/RE ⇔ TM | IA Discrete Math (Reg, DFA) ✎<br />IB Compiler Construction (CFG)<br />IB Computation Theory (TM)<br />IB Formal Model of Language                                                          |
| 4-2 | [Parsing Algorithms](./Note/Parsing%20outline.pdf)                   | outline and key points                                                   | IB Compiler, Formal language ✎<br />   ✓ Q [y20p4q4](https://www.cl.cam.ac.uk/teaching/exams/pastpapers/y2020p4q4.pdf)                                                                       |
| 4-3 | [CFG Parser ](./Note/Parsing.pdf)                                   | table driven parsers<br />LL(k), SLR(1), LR(1)                           | IB Compiler Construction ✎<br />✓ Q [y15p3q3](https://www.cl.cam.ac.uk/teaching/exams/pastpapers/y2015p3q3.pdf), [21p4q4](https://www.cl.cam.ac.uk/teaching/exams/pastpapers/y2021p4q4.pdf), etc |
| 4-4 | [Translation](./Note/Translation.pdf)                                | Continuous Passing Style<br />Defunctionalization to VM                  | ✓ IB Compiler Construction<br />■ [CPS @ CS6110-Ad_ProgLang](./Ref/IBCompiler/CPS.pdf)                                                                                                         |
| 4-5 | [Algos &amp; Complexity](./Note/Lists%20of%20Algorithms.pdf)         | P, NP, SPACE, etc                                                        | IA Algorithm; IB Complexity<br />II Randomized Algo, etc ✎                                                                                                                                 |
| 4-6 | [Quantum Computing](./Note/quantumComputing.pdf)                     | LA, gates, algos, QFT                                                    | II Quantum Computing                                                                                                                                                                          |

> *Reference:*

- Compiler Construction
  - [(S)LR @ Stanford CS143](./Ref/IBCompiler/LR%20and%20SLR%20Parsing.pdf); [CPS @ CS6110-Ad_ProgLang](./Ref/IBCompiler/CPS.pdf)
- Computation Theory
  - Supervision Sheet with solutions [1](./Ref/IBCompTheory/exer_sols_1.pdf) [2](./Ref/IBCompTheory/exer_sols_2.pdf) [3](./Ref/IBCompTheory/exer_sols_3.pdf). Source: [@Dimitrios Los](https://dimitrioslos.com/supervisions/)
  - [Supplementary notes on decidability](./Ref/IBCompTheory/Notes-Decidability.pdf)
    - by Andrej Ivašković (ai294), 23rd August 2019

#### ProgLang

> *Reference:*

- Prolog
  - Extra: [Prolog 99 Problems](./Ref/IBProlog/P-99_Ninety-Nine%20Prolog%20Problems.pdf)
  - Solutions: [First 12 Problems](https://github.com/danielchatfield/prolog-99-problems), credit: [@Daniel Chatfield](https://github.com/danielchatfield/)
- Semantics
  - [Evaluation Contexts @ CS6110-Ad_ProgLang](./Ref/IBSemantics/Evaluation%20Contexts.pdf)
    - `E[·]` Concise way to write context rule.
    - Lectured and examined [y2022p4q9](https://www.cl.cam.ac.uk/teaching/exams/pastpapers/y2022p4q9.pdf)

#### Others

> *Reference:*

- [Past Paper by Topics](./Past_Paper.html)
- [Supervision materials](https://dimitrioslos.com/supervisions/), credit: [@Dimitrios Los](https://dimitrioslos.com/academic.html)
- [Course work reference (2015)](https://github.com/danielchatfield/), credit: [@Daniel Chatfield](https://github.com/danielchatfield/)
- [ALevel-CST_Tripos Notes](https://github.com/ashwinahuja/Cambridge-Computer-Science-Tripos-Notes), credit: @ashwinahuja
