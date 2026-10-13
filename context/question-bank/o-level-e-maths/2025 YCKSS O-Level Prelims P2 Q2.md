---
title: "2025 YCKSS O-Level Prelims P2 Q2"
category: "question"
subject: "O-Level E Maths"
standard: "O-Level"
year: 2025
school: "YCKSS"
paper: 2
type: "prelims"
question_number: 2
question_type: "Structured"
marks: 9
page: "4–5"
topic:
  - "S1 Data handling and analysis"
  - "N3 Percentage"
lo:
  - "[[context/subjects/o-level-e-maths/learning-objectives/o-level-e-maths-S1f.md|S1f]]"
  - "[[context/subjects/o-level-e-maths/learning-objectives/o-level-e-maths-N3d.md|N3d]]"
difficulty_score: 5.7
difficulty_factors:
  - "factual_retrieval"
  - "conceptual_relationship"
  - "calculation_or_procedure"
  - "visual_or_data_interpretation"
cognitive_process: "Apply"
cognitive_subprocess: "Executing"
source_paper: "[[context/subjects/o-level-e-maths/past-year-papers/2025/YCKSS/2025_YCKSS_EMath_P2_QP-cleaned.md]]"
source_ms: "[[context/subjects/o-level-e-maths/past-year-papers/2025/YCKSS/2025_YCKSS_EMath_P2_MS-cleaned.md]]"
source_question: "Q2"
images: []
answers_scheme: true
answer_status: "Official mark scheme matched"
keepable_answer: false
tags:
  - "question-bank"
  - "yckss-2025"
  - "paper-2"














---

## Question

> **Marks:** (a)(i) 2, (a)(ii) 1, (b)(i) 1, (b)(ii) 2, (b)(iii) 1, (c) 2; total 9
> **Page:** 4–5

**(a)** On average, fruit seller A is able to sell 20 mangoes, 32 apples and 15 oranges in a day.
On average, fruit seller B is able to sell 15 mangoes, 35 apples and 18 oranges in a day.

The information can be represented by the matrix

$$
F=\begin{pmatrix}20&32&15\\15&35&18\end{pmatrix}.
$$

**(i)** Evaluate the matrix

$$
T=5F\begin{pmatrix}1\\1\\1\end{pmatrix}.
$$

[2]

**(ii)** State what each of the elements of $T$ represents. [1]

**(b)** Seller A sells a mango for 80 cents, an apple for 50 cents and an orange for 60 cents.
Seller B sells a mango for 70 cents, an apple for 40 cents and an orange for 50 cents.

**(i)** Represent this information in a $3\times 2$ matrix $C$. [1]

**(ii)** Evaluate the matrix $P=FC$. [2]

**(iii)** The cost price of all the fruits sold is &#36;10 for each seller.

Explain which seller made a higher profit. [1]

**(c)** In a promotion, both seller A and B decide to give a discount of $20\%$ for each mango and $10\%$ for each apple.

With the use of matrix multiplication, find a $3\times 2$ matrix $N$ where each element represents the new selling price of a mango, an apple and an orange by seller A and B respectively. [2]

## Answer Scheme

**(a) (i)** Evaluate $T=5F\begin{pmatrix}1\\1\\1\end{pmatrix}$.

$$
T=5\begin{pmatrix}20&32&15\\15&35&18\end{pmatrix}\begin{pmatrix}1\\1\\1\end{pmatrix}
$$

$$
T=5\begin{pmatrix}67\\68\end{pmatrix}
$$

$$
T=\begin{pmatrix}335\\340\end{pmatrix}
$$

> **Marker's Comments:** 1 mark awarded for matrix multiplication without the $\begin{pmatrix}1\\1\\1\end{pmatrix}$ matrix.

**(a) (ii)** State what each of the elements of $T$ represents.

The elements represent the total number of mangoes, apples and oranges sold by seller A and B respectively in 5 days.

> **Marker's Comments:** "Weekdays" not allowed. It is '5 days', "weekday" or "weekend" not mentioned. Total number, not average number.

**(b) (i)** Represent this information in a $3\times 2$ matrix $C$.

$$
C=\begin{pmatrix}80&70\\50&40\\60&50\end{pmatrix}
\quad\text{or}\quad
C=\begin{pmatrix}0.80&0.70\\0.50&0.40\\0.60&0.50\end{pmatrix}
$$

**(b) (ii)** Evaluate the matrix $P=FC$.

$$
P=\begin{pmatrix}20&32&15\\15&35&18\end{pmatrix}\begin{pmatrix}80&70\\50&40\\60&50\end{pmatrix}
$$

$$
P=\begin{pmatrix}4100&3430\\4030&3350\end{pmatrix}
\quad\text{or}\quad
P=\begin{pmatrix}41.00&34.30\\40.30&33.50\end{pmatrix}
$$

A1 for 2 correct elements. A2 for 4 correct elements.

**(b) (iii)** Explain which seller made a higher profit.

Seller A receives a total of &#36;41 while seller B receives &#36;33.50.
Seller A made a higher profit.

> **Marker's Comments:** "Total sales/total revenue" not "total selling price".

**(c)** Find matrix $N$.

$$
N=\begin{pmatrix}0.8&0&0\\0&0.9&0\\0&0&1\end{pmatrix}\begin{pmatrix}80&70\\50&40\\60&50\end{pmatrix}
$$

$$
N=\begin{pmatrix}64&56\\45&36\\60&50\end{pmatrix}
$$

> **Marker's Comments:** Many still do not know that the orders of matrices are important for matrix multiplication.
