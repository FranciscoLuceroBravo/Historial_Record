# Historial_Record
Original documentation (2012–2013) of the recursive powers method  connecting figurate numbers to Pythagorean congruent areas, developed  independently without specialized literature. Foundation of the  multifactorial operator family C^(k)_n(m) published in Zenodo  preprint (2026).
# Historical Record of the Recursive Powers Method

## Origin and Priority Documentation

This folder contains the original documentation of the recursive powers 
method and the multifactorial operator family C^(k)_n(m), developed 
independently by Francisco Javier Lucero Bravo beginning in 2012.

---

## Document 1: September 9, 2012

**File:** `2012_09_09_polygonal_numbers_formula.png`  
**Source:** Personal Facebook account (public post, timestamp verified)  
**URL:** facebook.com/photo/?fbid=42470060098830&set=a.3107005790537

### Content

A unified formula for generating triangular, oblong, square, and 
pentagonal numbers from any natural number X, derived independently 
using only a calculator. The post reads (translated from Spanish):

> "A formula to find triangular, oblong, square, and pentagonal numbers 
> from any natural number X. Without doubt this is my greatest 
> achievement in mathematics so far."

### Significance

This document establishes the earliest point of the research program: 
the observation that polygonal numbers of different types are 
structurally connected through a single algebraic expression. This 
connection, rediscovered independently without access to specialized 
literature, became the foundation for the recursive powers method 
developed in subsequent years.

The formula shown:

(X-1)·X/2 + ((2·(X/2)·(X+1)) - X)

unifies triangular numbers (T_n), oblong numbers (O_n), square 
numbers (C_n), and pentagonal numbers (P_n) within a single 
parametric expression in the natural number X.

---

## Document 2: June 5, 2013

**File:** `2013_06_05_recursive_powers_method_3levels.png`  
**Source:** Personal Facebook account (public post, timestamp verified)  
**URL:** facebook.com/photo/?fbid=10200853549077455&set=a.3107005790537

### Content

The recursive powers method presented explicitly across three levels:

**Level 1 — Hogben Centered Polygonal Numbers:**

X² - (X-1) = (X-1)² + X

**Level 2 — Oblong Numbers:**

[X³ - (X-1)²] - [(X-1)³ + X²] = X(X-1)

**Level 3 — Pythagorean Congruent Numbers:**

[X⁴ - (X-1)³] - [(X-1)⁴ + X³] = [X(X-1)][X + (X-1)]

### Method Description

The diagram explicitly identifies the structural components:

- **Difference between consecutive integers with consecutive powers**
  (left side of each equation)
- **Sum between consecutive integers with consecutive powers**  
  (right side subtracted)
- **Product between consecutive integers** (green: the result)
- **Sum between consecutive integers** (yellow: auxiliary factor)

### Significance

This document establishes the complete formulation of the recursive 
powers method as of June 2013. The three-level structure shows:

1. The same algebraic mechanism — differences of consecutive powers 
   between consecutive integers — generates qualitatively different 
   classes of figurate numbers at each level.

2. Level 3 produces [X(X-1)][X + (X-1)] = X(X-1)(2X-1), which is 
   precisely the foundational case C^(2)_n(1) of the multifactorial 
   operator family, the first instance generating congruent number areas.

3. The method was derived without knowledge of the existing literature 
   on congruent numbers, elliptic curves, or the Birch and 
   Swinnerton-Dyer conjecture.

---

## Development Timeline

| Date | Milestone |
|------|-----------|
| Sep 2012 | Unified polygonal formula derived via calculator |
| Jun 2013 | Recursive powers method formulated across 3 levels |
| 2025 | Generalization: fixed shift m=1 freed to parameter m ∈ [1,n-1] |
| 2025 | Full multifactorial family C^(k)_n(m) formulated |
| 2025 | k=3 identified as algebraically distinguished; birational equivalence with E_N established; orbital index k*(N) introduced |
| Feb 2026 | Preprint deposited: Zenodo DOI [your DOI here] |

---

## Connection to the Published Preprint

The recursive powers method documented here is the origin of all 
results in:

**Lucero Bravo, F.J. (2026).** "Arithmetic Compactness and Universal 
Generation: The k=3 Operator, Finite Siegel Points, and Dense 
Mordell-Weil Orbits in Congruent Number Theory."  
Zenodo. DOI: [your DOI here]

Specifically:

- The Level 3 result X(X-1)(2X-1) is E_4(n) = C^(2)_n(1) 
  (Section 3 of the preprint)
- The recursive structure E_k(n) = n^k - n^(k-1) - (n-1)^k - (n-1)^(k-1) 
  is Definition 1 of the preprint
- The generalization to C^(k)_n(m) with free parameter m is 
  Proposition 2 of the preprint

The 2013 diagram thus constitutes the original formulation of what 
the preprint develops into a complete parametric framework connecting 
figurate numbers, Pythagorean areas, and congruent number theory.

---

## Note on Independent Discovery

The results documented here were derived independently, without access 
to specialized mathematical literature, using only a calculator for 
numerical verification. The author was unaware at the time of:

- The connection to congruent numbers in the number-theoretic sense
- The theory of elliptic curves and Mordell-Weil groups
- The Birch and Swinnerton-Dyer conjecture
- Existing results by Tunnell (1983) or Coates-Wiles (1977)

The connection to these areas of mathematics was discovered 
progressively over the following years as the method was developed 
and its algebraic consequences explored.
