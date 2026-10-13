---
title: "2024 BMSS O-Level Prelims P2 Q4"
category: "question"
subject: "O-Level E Maths"
standard: "O-Level"
year: 2024
school: "BMSS"
paper: 2
type: "prelims"
question_number: 4
question_type: "Structured"
marks: 9
page: "8–9"
topic:
  - "N9 Matrices"
lo:
  - "[[context/subjects/o-level-e-maths/learning-objectives/o-level-e-maths-N9b.md|N9b]]"
difficulty_score: 4.8
difficulty_factors:
  - "factual_retrieval"
  - "conceptual_relationship"
  - "calculation_or_procedure"
cognitive_process: "Apply"
cognitive_subprocess: "Executing"
source_paper: "[[context/subjects/o-level-e-maths/past-year-papers/2024/BMSS/2024_BMSS_EMath_P2_QP-cleaned.md]]"
source_ms: "[[context/subjects/o-level-e-maths/past-year-papers/2024/BMSS/2024_BMSS_EMath_P2_MS-cleaned.md]]"
source_question: "Q4"
images: []
answers_scheme: true
answer_status: "Official mark scheme matched"
keepable_answer: false
tags:
  - "question-bank"
  - "bmss-2024"
  - "paper-2"














---

## Question

> **Marks:** 9
> **Page:** 8–9

Starkids Centre is organising a talent competition for children. Children can choose to compete in $3$ categories – singing, dancing and acting.

Matrix $\mathbf{E}$ shows the number of boys and girls in each category for the age group $5$ to $8$ years old.

$$
\mathbf{E}=\begin{pmatrix}5&8\\ 7&4\\ 6&7\end{pmatrix}
\begin{array}{l}\text{Singing}\\ \text{Dancing}\\ \text{Acting}\end{array}
$$

Columns are Boys, Girls.

Matrix $\mathbf{F}$ shows the number of boys and girls in each category for the age group $9$ to $12$ years old.

$$
\mathbf{F}=\begin{pmatrix}12&9\\ 8&10\\ 15&11\end{pmatrix}
\begin{array}{l}\text{Singing}\\ \text{Dancing}\\ \text{Acting}\end{array}
$$

Columns are Boys, Girls.

**(a)** Evaluate the matrix $\mathbf{T}=\mathbf{E}+\mathbf{F}$. [1]

**(b)** Each child is charged a registration fee for the competition. The registration is ＄30 for singing, ＄25 for dancing and ＄22 for acting. Represent the fees in a $1\times 3$ matrix $\mathbf{C}$. [1]

**(c)** Evaluate the matrix $\mathbf{M}=\mathbf{CT}$ and state what the elements in matrix $\mathbf{M}$ represent. [3]

**(d)** Using matrix multiplication, calculate the total amount of registration fees collected for this competition. [2]

**(e)** Starkids Centre decides to organise a similar competition for teenagers aged $13$ to $18$ years old. As compared to the competition for children aged $5$ to $8$ years old, the registration fees for teenagers is increased by $10\%$ for singing, $20\%$ for dancing and $15\%$ for acting.

Using matrix multiplication, calculate the registration fees for teenagers for each category. Give your answer in matrix form. [2]

## Answer Scheme

**(a)**

$$
\mathbf{T}=\begin{pmatrix}5&8\\ 7&4\\ 6&7\end{pmatrix}+\begin{pmatrix}12&9\\ 8&10\\ 15&11\end{pmatrix}=\begin{pmatrix}17&17\\ 15&14\\ 21&18\end{pmatrix}
$$

[B1]

**(b)** $\mathbf{C}=\begin{pmatrix}30&25&22\end{pmatrix}$ [B1]

**(c)**

$$
\mathbf{M}=\begin{pmatrix}30&25&22\end{pmatrix}\begin{pmatrix}17&17\\ 15&14\\ 21&18\end{pmatrix}=\begin{pmatrix}1347&1256\end{pmatrix}
$$

[B1], [B1]

$\mathbf{M}$ represents the registration fees collected from boys and girls respectively. [B1]

**(d)**

$$
\begin{pmatrix}1347&1256\end{pmatrix}\begin{pmatrix}1\\ 1\end{pmatrix}
$$

[M1]

$$
=\begin{pmatrix}2603\end{pmatrix}
$$

[A1]

Total collected is ＄2603.

**(e)** As compared with the competition for children, the teenage fees are increased by $10\%$ for singing, $20\%$ for dancing and $15\%$ for acting.

$$
\begin{pmatrix}30&25&22\end{pmatrix}\begin{pmatrix}1.1&0&0\\ 0&1.2&0\\ 0&0&1.15\end{pmatrix}
$$

[M1]

$$
=\begin{pmatrix}33&30&25.3\end{pmatrix}
$$

[A1]
