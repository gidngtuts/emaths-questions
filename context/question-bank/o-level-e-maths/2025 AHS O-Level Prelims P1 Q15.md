---
title: "2025 AHS O-Level Prelims P1 Q15"
category: "question"
subject: "O-Level E Maths"
standard: "O-Level"
year: 2025
school: "AHS"
paper: 1
type: "prelims"
question_number: 15
question_type: "Structured"
marks: 7
page: "12–14"
topic:
  - "N6 Functions and graphs"
lo:
  - "[[context/subjects/o-level-e-maths/learning-objectives/o-level-e-maths-N6f.md|N6f]]"
difficulty_score: 3.4
difficulty_factors:
  - "conceptual_relationship"
  - "calculation_or_procedure"
cognitive_process: "Apply"
cognitive_subprocess: "Executing"
source_paper: "[[context/subjects/o-level-e-maths/past-year-papers/2025/AHS/2025_AHS_EMath_P1_QP-cleaned.md]]"
source_ms: "[[context/subjects/o-level-e-maths/past-year-papers/2025/AHS/2025_AHS_EMath_P1_MS-cleaned.md]]"
source_question: "Q15"
images: []
answers_scheme: true
answer_status: "Official mark scheme matched"
keepable_answer: false
tags:
  - "question-bank"
  - "ahs-2025"
  - "paper-1"














---

## Question

> **Marks:** (a) 1, (b) 3, (c) 3; total 7
> **Page:** 12–14

A new type of energy harvesting device is being developed to capture energy from small environmental vibrations. The engineers observe that the fraction of energy captured by the device during $n$th second of continuous operation, relative to its maximum capacity, follows a specific pattern.

| Time (second) | Fraction of energy captured relative to its maximum capacity |
| --- | --- |
| 1st | $\dfrac{1}{2}\left(1-\dfrac{1}{2}\right)$ |
| 2nd | $\dfrac{1}{2}\left(\dfrac{1}{2}-\dfrac{1}{3}\right)$ |
| 3rd | $\dfrac{1}{2}\left(\dfrac{1}{3}-\dfrac{1}{4}\right)$ |
| $\ldots$ | $\ldots$ |
| $n$th | $\ldots$ |

**(a)** Write down the fraction of energy captured for the $n$th second of operation. [1]

**(b)** The team needs to find the total energy captured after $K$ seconds of continuous operation. Show that the total energy captured after $K$ seconds is $\dfrac{1}{2}\left(1-\dfrac{1}{K+1}\right)$. [3]

**(c)** The energy harvesting device is considered a success if it is able to harvest at least $49.8\%$ of its maximum capacity. Find the minimum number of seconds for which the device is considered a success. [3]

## Answer Scheme

**(a)** Write down the fraction of energy captured for the $n$th second of operation.

$$
\dfrac{1}{2}\left(\dfrac{1}{n}-\dfrac{1}{n+1}\right)
$$

**B1**

**(b)** Show that the total energy captured after $K$ seconds is $\dfrac{1}{2}\left(1-\dfrac{1}{K+1}\right)$.

$$
\begin{aligned}
&\dfrac{1}{2}\left(1-\dfrac{1}{2}\right)+\dfrac{1}{2}\left(\dfrac{1}{2}-\dfrac{1}{3}\right)+\dfrac{1}{2}\left(\dfrac{1}{3}-\dfrac{1}{4}\right)+\cdots\\
&+\dfrac{1}{2}\left(\dfrac{1}{K-1}-\dfrac{1}{K}\right)+\dfrac{1}{2}\left(\dfrac{1}{K}-\dfrac{1}{K+1}\right)\\
&=\dfrac{1}{2}\left(1-\dfrac{1}{K+1}\right)
\end{aligned}
$$

**M1** Listing. **M1** Factorise half. **A1**

**(c)** The energy harvesting device is considered a success if it is able to harvest at least $49.8\%$ of its maximum capacity. Find the minimum number of seconds for which the device is considered a success.

$$
\begin{aligned}
\dfrac{1}{2}\left(1-\dfrac{1}{K+1}\right)&\geq 0.498\\
1-\dfrac{1}{K+1}&\geq 0.996\\
0.004&\geq\dfrac{1}{K+1}\\
K+1&\geq\dfrac{1}{0.004}\\
K+1&\geq 250\\
K&\geq 249
\end{aligned}
$$

**M1** form inequality. **M1** simplify. **A1**
