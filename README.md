# Computer Science Tripos

## Source

- Cambridge Lecture Notes & Textbooks
- Example sheets & Past papers
- Online resources
  - wiki, similar courses globally
- Related notes
  - [Paper1-9 Notes @ashwinahuja](https://github.com/ashwinahuja/Cambridge-Computer-Science-Tripos-Notes)
  - [Supervision Reference](./Supervision_Reference.md)

## Category

- ✎ Lecture Note summary
- ✓ Past Paper Questions
- ■ Related / extra notes around the topics

## Notes

*Listed by written time, errors would be updated if found.*

[1. Relations and Functions](./Note/Relation_Function.pdf)

Covering *the definition, properties and relationship between key concepts.*

- ✎ IA Discrete Mathematics

[2. Memory Calculation](./Note/Memory%20Calculation.pdf)

Covering *how to interpret memory addresses in page table, TLB and cache.*

- ✎ IA OS
  - page table and TLB
- ✎ IB Computer Architecture
  - cache
  - ✓ MSI+Cacheline Question [y2021p5q3](https://www.cl.cam.ac.uk/teaching/exams/pastpapers/y2021p5q3.pdf)

[3. Concurrency Control](./Note/Concurrency%20Control.pdf)

Covering *concurrency control for single object and transactions afterwards.*

- ✎ IB Computer Architecture
  - Memory consistency and atomicity
- ✎ IB Concurrent System

[4. Formal Languages](./Note/Formal%20Languages.pdf)

Covering *around Chomsky hierarchy.*

- ✎ IA Discrete Math
  - Regular Languages and finite automata
  - Pumping Lemma for Regular Languages
- ✎ IB Compiler Construction
  - CFG, PDA
- ✎ IB Formal Model of Language
  - Pumping Lemma for Language of CFG
  - Chomsky hierarchy
- ✎ IB Computation Theory
  - TM

[5. CFG Parser](./Note/Parsing.pdf)

Covering *table driven parsers breakdown.*

- ✎ IB Compiler Construction
  - LL(k), SLR(1), LR(1)

[6. Parsing Algorithms Outline](./Note/Parsing%20outline.pdf)

Covering *a list of wider parsers key points.*

- ✎ IB Compiler Construction
- ✎ IB Formal Model of language

[7. CPS and Defun (Updated)](./Note/CPS-Defun-y2017p3q4.pdf)

Covering *Continuous Passing Style and Defunctionalization.*

- IB Compiler Construction

  - Adapting recursive calls to iterative one, following the steps introduced by the Lecturer.
  - ✓ Question from [y2017p23q4](https://www.cl.cam.ac.uk/teaching/exams/pastpapers/y2017p23q4.pdf) and more.

    - Invariant for Continuous Passing Style.

    ```
    c (eval e)=eval_cps c e
    ```

    - Defunctionalization

    ```
    ID, PAIR1, PAIR2, FUNC
    ```
  - ■ [CPS @ CS6110-Ad_ProgLang](./Ref/IBCompiler/CPS.pdf)

[8. Network by Analogy](./Note/Network%20by%20Analogy.pdf)

Covering key concepts *in five layers of Computer Network by analogy.*

- IB Computer Networking

## See more

- Related notes
  - [Paper1-9 Notes @ashwinahuja](https://github.com/ashwinahuja/Cambridge-Computer-Science-Tripos-Notes)
  - [Supervision Reference](./Supervision_Reference.md)
