# My Discrete Math RePository

## Homework 2 -202655358(dolmenge0909) 이명서

## Equation editing

| # | Text | Formula |
|---|------|---------|
| 1 | IF (P AND Q) THEN R | $(P \wedge Q) \to R$ |
| 2 | (P XOR Q) OR R | $(P \oplus Q) \vee R$ |
| 3 | NOT P IFF Q | $\neg P \leftrightarrow Q$ |
| 4 | FOR ALL x, P(x) | $(\forall x)P(x)$ |
| 5 | THERE EXISTS AN x, NOT Q(x) | $(\exists x)\neg Q(x)$ |
| 6 | IF P THEN Q EQUIVALENT TO NOT P OR Q | $P \to Q \equiv \neg P \vee Q$ |
| 7 | Euler's Identity | $e^{i\pi} + 1 = 0$ |
| 8 | SUM of n from 1 to 100 Equals 5050 | $\sum_{n=1}^{100} n = 5050$ |

---

## 2.2 Translate Sentences Into Logic Formulas

**Propositions:**
* $p$: "I study"
* $q$: "I will pass the course"
* $r$: "The professor accepts bribes"

**Translations:**
1. If I do not study, then I will only pass the course if the professor accepts bribes.
   * $\neg p \to (q \leftrightarrow r)$
2. If the professor accepts bribes, then I do not study.
   * $r \to \neg p$
3. The professor does not accept bribes, but I study and will pass the course.
   * $\neg r \wedge (p \wedge q)$
4. If I study, the professor will accept bribes and I will pass the course.
   * $p \to (r \wedge q)$
5. I will not pass the course but the professor accepts bribes.
   * $\neg q \wedge r$
