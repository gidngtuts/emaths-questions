---
title: "O-Level E-Maths — Key Algebra Formulae"
subject: O-Level E-Maths (4052)
topics:
  - algebraic identities
  - algebraic fractions
  - formula manipulation
  - quadratic expressions and graphs
  - indices
---

# O-Level E-Maths — Key Algebra Formulae

A compact reference to the algebra formulae discussed in the recent revision. The identities are useful for recognising patterns; the fraction rules help combine and simplify expressions; formula manipulation keeps rearrangements controlled.

## 1. Algebraic identities

### Square of a sum

$$
(a+b)^2 = a^2+2ab+b^2
$$

Read backwards when factorising:

$$
a^2+2ab+b^2=(a+b)^2
$$

### Square of a difference

$$
(a-b)^2 = a^2-2ab+b^2
$$

Read backwards when factorising:

$$
a^2-2ab+b^2=(a-b)^2
$$

**Pattern check:** the first and last terms are squares. The middle term is twice the product of their square roots, with the sign shown in the middle term.

### Difference of two squares

$$
a^2-b^2=(a+b)(a-b)
$$

The reverse is also useful:

$$
(a+b)(a-b)=a^2-b^2
$$

**Pattern check:** there are two square terms separated by subtraction. The factors are the sum and difference of the square roots.

## 2. Algebraic fractions

### Add or subtract

For non-zero denominators $B$ and $D$:

$$
\frac{A}{B}\pm\frac{C}{D}
=\frac{AD}{BD}\pm\frac{BC}{BD}
=\frac{AD\pm BC}{BD}
$$

Use a common denominator before combining. If the denominators have a simpler lowest common denominator than $BD$, use that instead.

### Negative signs

$$
\frac{A}{-B}=\frac{-A}{B}=-\frac{A}{B}
$$

A negative sign can be moved between the numerator, denominator, and whole fraction, but it must be kept consistently.

### Cancel common factors

For $B\ne0$ and $C\ne0$:

$$
\frac{AC}{BC}=\frac{A}{B}
$$

Cancel **factors** that multiply. Do not cancel terms separated by $+$ or $-$; factor first if possible.

## 3. Changing the subject of a formula

There is no single rearrangement formula for every question. Use these rules:

- Apply the same operation to both sides of an equation.
- Undo operations in the reverse order in which they were applied to the variable.
- Keep the requested variable alone on one side.
- If rearranging gives $x^2=K$, then $x=\pm\sqrt K$, unless the context restricts $x$ to positive values.
- When multiplying or dividing an inequality by a negative number, reverse the inequality sign.

## 4. Quadratics and their graphs

### Factor form from roots

If the $x$-intercepts are $r_1$ and $r_2$, then

$$
y=a(x-r_1)(x-r_2)
$$

Use a known point on the curve to determine $a$, if it is not already known.

### Completing the square

For a monic quadratic:

$$
x^2+bx+c=\left(x+\frac b2\right)^2+c-\left(\frac b2\right)^2
$$

For a general quadratic with $p\ne0$:

$$
px^2+qx+r=p\left(x+\frac{q}{2p}\right)^2+r-\frac{q^2}{4p}
$$

### Vertex form

$$
y=p(x-h)^2+k
$$

The turning point is $(h,k)$, and the axis of symmetry is $x=h$. The sign of $p$ shows the direction the curve opens: positive for upwards, negative for downwards.

## 5. Index laws

For the same non-zero base $a$:

$$
a^m\times a^n=a^{m+n}
$$

$$
\frac{a^m}{a^n}=a^{m-n}
$$

$$
(a^m)^n=a^{mn}
$$

$$
a^{-n}=\frac{1}{a^n}
$$

For positive integer $n$ (with roots defined in the number system being used):

$$
a^{1/n}=\sqrt[n]{a},\qquad a^{m/n}=\sqrt[n]{a^m}
$$

## Worked example — use a difference of squares to simplify a fraction

Simplify

$$
\frac{x+3}{x^2-9}
$$

Recognise the denominator as a difference of two squares:

$$
x^2-9=x^2-3^2=(x+3)(x-3)
$$

Substitute the factorised denominator, then cancel the common factor $x+3$:

$$
\frac{x+3}{x^2-9}
=\frac{x+3}{(x+3)(x-3)}
=\frac{1}{x-3}
$$

The original denominator cannot be zero, so $x\ne3$ and $x\ne-3$. In particular, the cancelled factor still gives the restriction $x\ne-3$.

### A reliable order of work

1. Look for a recognisable identity and factor before expanding.
2. Rewrite negative signs consistently.
3. Make denominators common before adding or subtracting fractions.
4. Cancel common factors only.
5. Keep any restrictions that made an original denominator non-zero.
6. For formula rearrangement, perform each operation on both sides and check the final subject is isolated.

## Sources

- E-Maths compilation note: `context/subjects/o-level-e-maths/notes/Secondary School Mathematics Material (All Level Compilation) Version 20250918B-cleaned.md` — Basic Algebraic Manipulation, Formula Manipulation, quadratic identities/completing the square, and Laws of Indices.
- Formula scope also reflects the algebraic identity and algebraic-fraction revision topics reviewed in Amanda's E-Maths audit; the example above is general and is not taken from a past-paper question.
