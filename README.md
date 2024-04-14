# Computer Science Tripos

## Resource

- Cambridge Lecture Notes  & Example sheets  / Textbooks
- [Past Papers](https://www.cl.cam.ac.uk/teaching/exams/pastpapers/)
  - [Past Paper by Topics](./Past_Paper.html)
- Online resources
  - wiki, similar courses globally
- Related
  - [Notes for A(S)Level to CST ](https://github.com/ashwinahuja/Cambridge-Computer-Science-Tripos-Notes)
    - Source: @ashwinahuja
  - [Supervision Reference](./Supervision_Reference.html)
  - [ExamTips](./Note/Tips.pdf)

## Category

- ✎ Lecture Note summary
- ✓ Past Paper Questions
- ■ Extra notes around the topics

## Notes

*Grouped by related lectures, errors would be updated if found.*

- Broad structure: 1 Math/AI, 2 Low-level (OS, Arch), 3 Theories, 4 Languages
- Note with (Tripos related courses > 1) is *cross-disciplinary* by nature.

| ID  | Notes                                                                         | Coverage                                                              | Tripos                                                                                                                                                                                       |
| --- | ----------------------------------------------------------------------------- | --------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [Relations and Functions](./Note/Relation_Function.pdf)                          | definition, properties and<br />relationship of key concepts.         | ✎ IA Discrete Math                                                                                                                                                                          |
| 1-2 | [Standard Random Variables](./Note/Standard%20Random%20Variables.pdf)            | Discrete/Continuous RV<br />Joint/marginal probability                | ✎ IA Intro to Probaility/NST Math<br />IB Data Science, etc                                                                                                                                 |
| 1-3 | [Machine Learning](https://peterhuistyping.github.io/Machine_Learning_Guidance/) | Probability, Data Science, ML<br />Practical ML, Troubleshooting      | IA Intro to Prob, MLRD<br />IB Data Science, AI<br />II MLBI, etc                                                                                                                            |
| 2-1 | [Data Segment and Linking](./Note/Data%20Segment%20and%20Linking.pdf)            | <br />Memory and ABI in<br />ProgLag - Compiler - OS - Arch           | ✎IA Java - IB C/C++<br />IA OS - IB Arch (RISC)<br />✓ IB Compiler Construction<br />IB Concurrent System                                                                                  |
| 2-2 | [Memory Calculation](./Note/Memory%20Calculation.pdf)                            | Interpret memory addresses<br />in Page tab, TLB and cache            | ✎ IA OS<br />IB Computer Architecture<br />✓ MSI+Cacheline Q [y21p5q3](https://www.cl.cam.ac.uk/teaching/exams/pastpapers/y2021p5q3.pdf)                                                     |
| 2-3 | [Comparative Architectures](./Note/Comparative%20Architectures.pdf)              | Arch design tradeoff                                                  | ■ IB Arch & II Ad Arch<br />IB Compiler Construction                                                                                                                                        |
| 3-1 | [Concurrency Control](./Note/Concurrency%20Control.pdf)                          | concurrent control for single obj<br /> and transactions afterwards. | ✎ IB Architecture (Mem ACID)<br />IB Concurrent System                                                                                                                                      |
| 3-2 | [Clocks Broadcast Replication](./Note/Clocks%20Broadcast%20Replication.pdf)      | Clocks, causality, broadcast                                          | ✎✓ IB Distributed, Network                                                                                                                                                                 |
| 3-3 | [Network by Analogy](./Note/Network%20by%20Analogy.pdf)                          | five layers of OSI                                                    | IB Computer Networking                                                                                                                                                                       |
| 3-4 | [Lists of Algorithms](./Note/Lists%20of%20Algorithms.pdf)                        | Algo, I/O, Complexity (NP)                                           | ✎ IA Algorithm; IB Complexity<br />II Randomized Algo, etc                                                                                                                                |
| 3-5 | [HCI Principles](./Note/HCI.pdf)                                                 | Heuristic Evaluation,<br />  Gestalt Cognitive                        | ✎ IA Interaction Design<br />IB Further HCI                                                                                                                                                |
| 4-1 | [Formal Languages <br />and Automata](./Note/Formal%20Languages.pdf)             | Chomsky hierarchy<br />Reg ⇔ DFA<br />CFG ⇔ PDA<br />CSG/RE ⇔ TM  | ✎ IA Discrete Math (Reg, DFA)<br />IB Compiler Construction (CFG)<br />IB Computation Theory (TM)<br />IB Formal Model of Language                                                          |
| 4-2 | [CFG Parser (Updated)](./Note/Parsing.pdf)                                      | table driven parsers breakdown<br />LL(k), SLR(1), LR(1)              | ✎ IB Compiler Construction<br />✓ Q [y15p3q3](https://www.cl.cam.ac.uk/teaching/exams/pastpapers/y2015p3q3.pdf), [21p4q4](https://www.cl.cam.ac.uk/teaching/exams/pastpapers/y2021p4q4.pdf), etc |
| 4-3 | [Parsing Algorithms Outline](./Note/Parsing%20outline.pdf)                       | a list of parsers key points.                                         | ✎ IB Compiler, Formal language<br />   ✓ Q[y20p4q4](https://www.cl.cam.ac.uk/teaching/exams/pastpapers/y2020p4q4.pdf)                                                                         |
| 4-4 | [CPS and Defun (Updated)](./Note/CPS-Defun-y2017p3q4.pdf)                        | Continuous Passing Style<br />Defunctionalization                     | ✓ Q[y17p23q4](https://www.cl.cam.ac.uk/teaching/exams/pastpapers/y2017p23q4.pdf) <br />IB Compiler Construction                                                                               |

### Extra Notes

7: CPS and Defunctionalization

- Adapting recursive calls to iterative one, following the steps introduced by the Lecturer.

  - Invariant for Continuous Passing Style.

  ```
  c (eval e)=eval_cps c e
  ```

  - ■ [CPS @ CS6110-Ad_ProgLang](./Ref/IBCompiler/CPS.pdf)
  - Defunctionalization

  ```
  ID, PAIR1, PAIR2, FUNC
  ```

## Related

- [Past Paper by Topics](./Past_Paper.html)
- [Supervision Reference](./Supervision_Reference.html)
