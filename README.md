# 📘 Chapter 3 — Bayes’ Theorem

---

## 🧩 Concept Snapshot

> **Bayes’ Theorem** lets us *revise a prior belief* once new evidence appears.  
> It flips a conditional probability from P(B | A) to P(A | B).

P(A∣B)=P(B∣A)P(A)/P(B)

	​

---

## 🧠 Intuition

| Term | Meaning | Example (Credit Risk) |
|------|----------|-----------------------|
| Prior | Belief before evidence | 4 % chance of default |
| Likelihood | Chance of evidence if event true | 70 % miss EMI given default |
| Evidence | Overall probability of evidence | Weighted average of both cases |
| Posterior | Updated belief after evidence | ≈ 22.6 % default given miss EMI |

Bayes = **Prior × Likelihood / Evidence**

---

## 💼 Business & Finance Applications

| Domain | Use Case | Meaning of Posterior |
|---------|-----------|----------------------|
| Credit Risk | P(Default \| Miss EMI) | Updated borrower risk |
| Fraud Detection | P(Fraud \| Alert) | True fraud rate after flag |
| Marketing | P(Convert \| Click) | Conversion probability |
| Medical Testing | P(Disease \| Positive) | Diagnostic accuracy 
