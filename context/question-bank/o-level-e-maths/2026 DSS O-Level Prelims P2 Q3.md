---
title: "2026 DSS O-Level Prelims P2 Q3"
category: "question"
subject: "O-Level E Maths"
standard: "O-Level"
year: 2026
school: "DSS"
paper: 2
type: "prelims"
question_number: 3
question_type: "Structured"
marks: 9
page: "8–9"
topic:
  - "N9 Matrices"
  - "N3 Percentage"
lo:
  - "[[context/subjects/o-level-e-maths/learning-objectives/o-level-e-maths-N9b.md|N9b]]"
  - "[[context/subjects/o-level-e-maths/learning-objectives/o-level-e-maths-N3d.md|N3d]]"
difficulty_score: 4.8
difficulty_factors:
  - "factual_retrieval"
  - "calculation_or_procedure"
  - "visual_or_data_interpretation"
cognitive_process: "Apply"
cognitive_subprocess: "Executing"
source_paper: "[[context/subjects/o-level-e-maths/past-year-papers/2026/DSS/2026_DSS_EMath_P2_QP-cleaned.md]]"
source_ms: "[[context/subjects/o-level-e-maths/past-year-papers/2026/DSS/2026_DSS_EMath_P2_MS-cleaned.md]]"
source_question: "Q3"
images: []
answers_scheme: true
answer_status: "Official mark scheme matched"
keepable_answer: false
tags:
  - "question-bank"
  - "dss-2026"
  - "paper-2"














---

## Question

> **Marks:** (a) 1, (b) 1, (c) 2, (d) 1, (e) 4; total 9
> **Page:** 8–9

A tour agency sold tour packages to Japan and Korea during a weekend travel fair.
The usual cost of each Japan package is \$3700.
The usual cost of each Korea package is \$3000.
This information can be represented by the matrix $\mathbf{C}=\begin{pmatrix}3700&3000\end{pmatrix}$.
The tour agency gave a $5\%$ discount to all the tour packages sold during the travel fair.
	The discounted costs of the packages can be represented by the matrix $\mathbf{D}$, where $\mathbf{D}=k\mathbf{C}$.

The number of tour packages sold to each of the destinations during the travel fair is shown in the table below.

| Destination | Number of Packages sold |  |  |
| --- | --- | --- | --- |
|  | Fri | Sat | Sun |
| Japan | 23 | 18 | 39 |
| Korea | 17 | 31 | 44 |

**(a)** Represent the number of tour packages sold in a $2\times 3$ matrix $\mathbf{N}$. [1]

**(b)** State the value of $k$. [1]

**(c)** Evaluate the matrix $\mathbf{R}=\mathbf{D}\mathbf{N}$. [2]

**(d)** State what the elements of $\mathbf{R}$ represent. [1]

**(e)** In addition to the sales made at the travel fair, the agency sold 132 Japan tour packages and 95 Korea tour packages that month without any discount given.

Calculate the percentage of the month's overall sales revenue that came from the travel fair. [4]

## Answer Scheme

**(a)**

$$
\mathbf{N}=\begin{pmatrix}23&18&39\\17&31&44\end{pmatrix}
$$

[B1]

**(b)** $k=0.95$ [B1]

**(c)** ecf from 3(b)

$$
\mathbf{D}=0.95\begin{pmatrix}3700&3000\end{pmatrix}=\begin{pmatrix}3515&2850\end{pmatrix}
$$

$$
\mathbf{R}=\begin{pmatrix}3515&2850\end{pmatrix}\begin{pmatrix}23&18&39\\17&31&44\end{pmatrix}=\begin{pmatrix}129295&151620&262485\end{pmatrix}
$$

[M1, A1]

**(d)** The elements of $\mathbf{R}$ represent the total cost of the discounted packages sold at the travel fair on Friday, Saturday and Sunday respectively. [B1]

The scheme prints "represents".

**(e)** ecf from 3(c)

Total cost of packages sold outside of the travel fair

$$
=132(\$3700)+95(\$3000)=\$773400
$$

Total cost of packages sold during the travel fair

$$
=\$129295+\$151620+\$262485=\$543400
$$

Month's total sales

$$
=\$773400+\$543400=\$1316800
$$

$$
\frac{543400}{1316800}\times 100\%=41.3\%\text{ (3 sig. fig.)}
$$

[M1, M1, M1, A1]
