---
title: "2026 DSS O-Level Prelims P2 Q7"
category: "question"
subject: "O-Level E Maths"
standard: "O-Level"
year: 2026
school: "DSS"
paper: 2
type: "prelims"
question_number: 7
question_type: "Structured"
marks: 10
page: "14–15"
topic:
  - "S2 Probability"
lo:
  - "[[context/subjects/o-level-e-maths/learning-objectives/o-level-e-maths-S2c.md|S2c]]"
difficulty_score: 5.3
difficulty_factors:
  - "conceptual_relationship"
  - "calculation_or_procedure"
  - "visual_or_data_interpretation"
cognitive_process: "Apply"
cognitive_subprocess: "Executing"
source_paper: "[[context/subjects/o-level-e-maths/past-year-papers/2026/DSS/2026_DSS_EMath_P2_QP-cleaned.md]]"
source_ms: "[[context/subjects/o-level-e-maths/past-year-papers/2026/DSS/2026_DSS_EMath_P2_MS-cleaned.md]]"
source_question: "Q7"
images: 
  - "[[context/subjects/o-level-e-maths/past-year-papers/2026/DSS/images/Dunman-2026-Emaths-Prelims-Paper-2-pages/page-14.png]]"
answers_scheme: true
answer_status: "Official mark scheme matched"
keepable_answer: false
tags:
  - "question-bank"
  - "dss-2026"
  - "paper-2"














---

## Question

> **Marks:** (a) 3, (b) 3, (c) 2, (d) 1, (e) 1; total 10
> **Page:** 14–15

A bag contains $n$ beads.
7 of the beads are red and the rest are white.
There are more white beads than red beads.
Two beads are taken from the bag, at random, without replacement.

**(a)** Complete the tree diagram. [3]

![Question 7 tree diagram](../../subjects/o-level-e-maths/past-year-papers/2026/DSS/images/Dunman-2026-Emaths-Prelims-Paper-2-pages/page-14.png)

Printed probabilities on the diagram: first bead Red $\dfrac{7}{n}$; second bead Red given Red $\dfrac{6}{n-1}$; second bead Red given White $\dfrac{7}{n-1}$. The remaining three branches are blank.

**(b)** The probability that both beads taken are of the same colour is $\dfrac{11}{18}$.

Show that $n^{2}-37n+252=0$. [3]

**(c)** By factorising $n^{2}-37n+252=0$, find the values of $n$. [2]

**(d)** Explain why one of the solutions in **part (c)** must be rejected. [1]

**(e)** Find, as a fraction in its simplest form, the probability that at least one of the two beads chosen is white colour. [1]

## Answer Scheme

**(a)** Completed tree diagram. [B3]

The scheme drawing is on the same marking-scheme page as the graph for Question 6. Blanks are the white branches:

- first bead White: $\dfrac{n-7}{n}$
- second bead White given Red: $\dfrac{n-7}{n-1}$
- second bead White given White: $\dfrac{n-8}{n-1}$

![Question 7 tree on the scheme](../../subjects/o-level-e-maths/past-year-papers/2026/DSS/images/Dunman-2026-Emaths-Paper-2-MS-pages/page-06.png)

**(b)** Formulate the equation. Simplify to a non-fractional equation.

$$
\frac{7}{n}\left(\frac{6}{n-1}\right)+\frac{n-7}{n}\left(\frac{n-8}{n-1}\right)=\frac{11}{18}
$$

$$
\frac{42+(n-7)(n-8)}{n(n-1)}=\frac{11}{18}
$$

$$
18(42+n^{2}-15n+56)=11n(n-1)
$$

$$
7n^{2}-259n+1764=0
$$

$$
n^{2}-37n+252=0\quad(\text{shown})
$$

[M1, M1, A1]

**(c)** $(n-9)(n-28)=0$, so $n=9$ or $28$. Or using the general formula. [M1, A1]

**(d)** Since there are more white beads than red beads, if $n=9$, then there are only 2 white beads which is less than the red beads. Therefore $n\neq 9$. [B1]

**(e)**

$$
P(\text{at least one white})=1-\frac{11}{18}=\frac{7}{18}
$$

The scheme labels this line "P(two beads chosen are of different colours)". [B1]
