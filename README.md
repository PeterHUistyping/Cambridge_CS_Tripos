# Computer Science Tripos

## Source

- Cambridge Lecture Notes & Textbooks
- Example sheets & Past papers
- Online resources
  - wiki, similar courses globally
- Related notes
  - [A(S)Level-Paper1-9 Notes @ashwinahuja](https://github.com/ashwinahuja/Cambridge-Computer-Science-Tripos-Notes)
  - [Supervision Reference](./Supervision_Reference.md)

## Category

- ✎ Lecture Note summary
- ✓ Past Paper Questions
- ■ Related / extra notes around the topics

## Notes

*Grouped by related lectures, errors would be updated if found.*

| ID  | Notes                                                              | Coverage                                                                 | Tripo                                                                                                                                                                                                     |
| --- | ------------------------------------------------------------------ | ------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [Relations and Functions](./Note/Relation_Function.pdf)               | definition, properties and<br />relationship of key concepts.            | ✎ IA Discrete Math                                                                                                                                                                                       |
| 2-1 | [Data Segment and Linking](./Note/Data%20Segment%20and%20Linking.pdf) | Memory and ABI                                                           | ✎IA Java - IB C/C++<br />IA OS - IB Arch (RISC)<br />IB Compiler Construction<br />✓ Stack Question [2014p3q4](https://www.cl.cam.ac.uk/teaching/exams/pastpapers/y2014p3q4.pdf)<br />IB Concurrent System |
| 2-2 | [Memory Calculation](./Note/Memory%20Calculation.pdf)                 | Interpret memory addresses<br />in page table, TLB and cache.            | ✎ IA OS<br />IB Computer Architecture<br />✓ MSI+Cacheline Q [y2021p5q3](https://www.cl.cam.ac.uk/teaching/exams/pastpapers/y2021p5q3.pdf)                                                                |
| 3   | [Concurrency Control](./Note/Concurrency%20Control.pdf)               | concurrency control for single object<br /> and transactions afterwards. | ✎ IB Architecture (Mem ACID)<br />IB Concurrent System                                                                                                                                                   |
| 4   | [Formal Languages](./Note/Formal%20Languages.pdf)                     | Chomsky hierarchy.                                                       | ✎ IA Discrete Math (Reg, DFA)<br />IB Compiler Construction (CFG)<br />IB Formal Model of Language<br />IB Computation Theory (TM)                                                                       |
| 5   | [CFG Parser](./Note/Parsing.pdf)                                      | table driven parsers breakdown.<br />LL(k), SLR(1), LR(1)                | ✎ IB Compiler Construction                                                                                                                                                                               |
| 6   | [Parsing Algorithms Outline](./Note/Parsing%20outline.pdf)            | a list of wider parsers key points.                                      | ✎ IB Compiler Construction<br />IB Formal Model of language                                                                                                                                              |
| 7   | [CPS and Defun (Updated)](./Note/CPS-Defun-y2017p3q4.pdf)             | Continuous Passing Style and<br />Defunctionalization.                   | IB Compiler Construction<br />✓ Q from [y2017p23q4](https://www.cl.cam.ac.uk/teaching/exams/pastpapers/y2017p23q4.pdf)                                                                                     |
| 8   | [Network by Analogy](./Note/Network%20by%20Analogy.pdf)               | concepts in five layers of OSI                                           | IB Computer Networking                                                                                                                                                                                    |

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

## See more

- Related notes
  - [Paper1-9 Notes @ashwinahuja](https://github.com/ashwinahuja/Cambridge-Computer-Science-Tripos-Notes)
  - [Supervision Reference](./Supervision_Reference.md)
