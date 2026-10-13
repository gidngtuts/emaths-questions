---
title: "2025 SJI O-Level Prelims P1 Q23"
category: "question"
subject: "O-Level E Maths"
standard: "O-Level"
year: 2025
school: "SJI"
paper: 1
type: "prelims"
question_number: 23
question_type: "Structured"
marks: 6
page: "20–21"
topic:
  - "N9 Matrices"
  - "N1 Numbers and their operations"
lo:
  - "[[context/subjects/o-level-e-maths/learning-objectives/o-level-e-maths-N9b.md|N9b]]"
  - "[[context/subjects/o-level-e-maths/learning-objectives/o-level-e-maths-N1e.md|N1e]]"
difficulty_score: 2.9
difficulty_factors:
  - "factual_retrieval"
  - "calculation_or_procedure"
cognitive_process: "Apply"
cognitive_subprocess: "Executing"
source_paper: "[[context/subjects/o-level-e-maths/past-year-papers/2025/SJI/2025_SJI_EMath_P1_QP-ANS-cleaned.md]]"
source_ms: "[[context/subjects/o-level-e-maths/past-year-papers/2025/SJI/2025_SJI_EMath_P1_MS-cleaned.md]]"
source_question: "Q23"
images: []
answers_scheme: true
answer_status: "Official mark scheme matched"
keepable_answer: false
tags:
  - "question-bank"
  - "sji-2025"
  - "paper-1"










---

## Question

> **Marks:** (a) 1, (b) 2, (c) 1, (d) 2; total 6
> **Page:** 20–21

A paint shop mixes three base colours (Red, Blue, Yellow) to create three shades, A, B, and C.
1 can of Shade A needs 2 litres of red, 3 litres of blue and 1 litre yellow base colours.
1 can of Shade B needs 1 litre of red, 2 litres of blue and 4 litres of yellow base colours.
1 can of Shade C needs 3 litres of red, 1 litre of blue and 2 litres of yellow base colours.
The matrix $M$ shows the number of litres of each base colour needed for 1 can of each shade.

$$
M=\begin{pmatrix}
2 & 1 & 3 \\
3 & 2 & 1 \\
1 & 4 & 2
\end{pmatrix}
\begin{matrix}
\text{Red} \\
\text{Blue} \\
\text{Yellow}
\end{matrix}
$$

Columns are Shade A, Shade B and Shade C.

**(a)** The shop wants to make 4 cans of Shade A, 2 cans of Shade B, and $x$ cans of Shade C.
Represent this information in a $3\times 1$ column matrix, $N$, in terms of $x$. [1]

**(b)** Find, in terms of $x$, the matrix $L=MN$. [2]

**(c)** State what each of the element in matrix $L$ represents. [1]

**(d)** The shop has 25 litres of red, 25 litres of blue, and 25 litres of yellow base colours in stock.
Find the largest integer value of $x$ so that none of the base colours runs out. [2]

## Answer Scheme

**(a)**

$$
N=\begin{pmatrix}4\\2\\x\end{pmatrix}
$$

**(b)**

$$
L=\begin{pmatrix}2&1&3\\3&2&1\\1&4&2\end{pmatrix}\begin{pmatrix}4\\2\\x\end{pmatrix}=\begin{pmatrix}10+3x\\16+x\\12+2x\end{pmatrix}
$$

**(c)** Matrix $L$ represents the total litres of red, blue, and yellow base colors, respectively, needed by the shop to create the three shades, A, B, and C.

OR

$10+3x$ represents the total litres of red base colour needed by the shop to create the 3 shades, A, B and C.

$16+x$ represents the total litres of blue base colour needed by the shop to create the 3 shades, A, B and C.

$12+2x$ represents the total litres of yellow base colour needed by the shop to create the 3 shades, A, B and C.

**(d)** Each colour must use at most 25 litres.

For Red:

$$
10+3x\leq 25,\quad x\leq 5
$$

For Blue:

$$
16+x\leq 25,\quad x\leq 9
$$

For Yellow:

$$
12+2x\leq 25,\quad x\leq 6.5
$$

Largest integer of $x=5$
