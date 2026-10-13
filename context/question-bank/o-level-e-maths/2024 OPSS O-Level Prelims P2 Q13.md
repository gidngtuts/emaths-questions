---
title: "2024 OPSS O-Level Prelims P2 Q13"
category: "question"
subject: "O-Level E Maths"
standard: "O-Level"
year: 2024
school: "OPSS"
paper: 2
type: "prelims"
question_number: 13
question_type: "Structured"
marks: 0
page: "21–22"
topic:
  - "S2 Probability"
lo:
  - "[[context/subjects/o-level-e-maths/learning-objectives/o-level-e-maths-S2c.md|S2c]]"
difficulty_score: 7.2
difficulty_factors:
  - "factual_retrieval"
  - "conceptual_relationship"
  - "calculation_or_procedure"
  - "mechanistic_or_causal_reasoning"
  - "discrimination_or_ambiguity"
  - "dependency_chain"
cognitive_process: "Apply"
cognitive_subprocess: "Executing"
source_paper: "[[context/subjects/o-level-e-maths/past-year-papers/2024/OPSS/2024_OPSS_EMath_P2_QP-cleaned.md]]"
source_ms: "[[context/subjects/o-level-e-maths/past-year-papers/2024/OPSS/2024_OPSS_EMath_P2_MS-cleaned.md]]"
source_question: "Q13"
images: []
answers_scheme: true
answer_status: "Official mark scheme matched"
keepable_answer: false
tags:
  - "question-bank"
  - "opss-2024"
  - "paper-2"














---

## Question

> **Marks:** (a) 2, (b) 2, (c) 6; total 10
> **Page:** 21–22

In a shooting game, the player has to shoot with a gun to capture a monster. The bullet from the gun has to land on a circular target on the monster so that a net will open up.
The circular target has four different sizes.
Target 1 is a big circle;
Target 2 is three quarters of the area of Target 1;
Target 3 is half of the area of Target 1;
Target 4 is one quarter of the area of Target 1.

**(a)** Sam estimates that the probability that he hits Target 1 is about 0.88. Given that the probability of hitting the circular target is proportional to its area, show that the probability that Sam hits Target 2 and Target 4 is estimated to be 0.66 and 0.44 respectively.

Even if the bullet hits the circular target, the monster might not be captured as it can break free from the net. The probability of successfully capturing the monster depends on the area and colour of the circular target, and the type of bullet that the player uses.

| | Target 1 | Target 2 | Target 3 | Target 4 |
| --- | --- | --- | --- | --- |
| Probability of Sam hitting the target | 0.88 | 0.66 | 0.44 | 0.22 |

| Targets of different sizes | Target 1 | Target 2 | Target 3 | Target 4 |
| --- | --- | --- | --- | --- |
| Multiplier for capturing monster | 0.7 | 0.8 | 0.95 | 0.5 |

| Targets of different colours | Green | Yellow | Orange | Red |
| --- | --- | --- | --- | --- |
| Multiplier for capturing monster | 0.9 | 0.7 | 0.5 | 0.4 |

| Types of bullets | Hollow Point | Soft Point | Flat Nose |
| --- | --- | --- | --- |
| Multiplier for capturing monster | 0.6 | 0.7 | 0.9 |

To calculate this probability, in-built multipliers are assigned to each of these three factors. For example, if a player uses a hollow point bullet and captures a monster with a yellow Target 3, the probability of successfully capturing the monster is given by $0.6\times 0.7\times 0.95=0.399$.

**(b)** Show that the estimated probability that Sam will hit and capture a monster with an orange Target 4 using a Flat Nose bullet is 0.0495.

In the game, the target changes colour from green to yellow to orange to red and finally back to green. Each change occurs every second. In addition, the target also changes its size from Target 1 to 2 to 3 to 4 and then back to Target 1. Each change also occurs every second. For example, if a monster appears with a yellow Target 3, it will change to an orange Target 4 in the next second, and then a red Target 1 in the following second.

**(c)** At time $t=0$ seconds, Sam sees a monster with a red Target 2. He only has one Soft Point bullet. State the colour, Target size and find the maximum probability and the number of seconds Sam should take to shoot at the monster in order to maximise his chance of hitting and capturing it. Justify your decision and show your calculations clearly.

## Answer Scheme

**(a)** $\dfrac{3}{4}\times 0.88=0.66$ and $\dfrac{1}{2}\times 0.88=0.44$

**(b)** $0.5\times 0.5\times 0.22\times 0.9=0.0495$

**(c)** With a Soft Point bullet (multiplier 0.7):

| Wait | Colour | Target | Probability |
| --- | --- | --- | --- |
| 0 s | Red | 2 | $0.66\times 0.8\times 0.4\times 0.7=0.14784$ |
| 1 s | Green | 3 | $0.44\times 0.95\times 0.9\times 0.7=0.26334$ |
| 2 s | Yellow | 4 | $0.22\times 0.5\times 0.7\times 0.7=0.0539$ |
| 3 s | Orange | 1 | $0.88\times 0.7\times 0.5\times 0.7=0.2156$ |

The maximum is at green Target 3 after 1 second, with probability 0.26334.

The scheme’s last line says “green Target 2”; the calculated row is green Target 3.
