# Group rings — Problem Set 1

A 54-problem set on group rings, starting from the definition and ending at spherical
harmonics. Written to be worked by hand. Every problem carries a collapsed answer, and the
harder ones carry a separate hint.

**Read it here: https://mazerakham.github.io/group-rings/**

- [`index.html`](index.html) — the problem set
- [`ORIGIN.md`](ORIGIN.md) — how it came about, and what to expect from it

## Contents

| | Section | Problems |
|---|---|---|
| A | Definitions and first consequences | 1–7 |
| B | Hand computation in ℝ[D₄] | 8–15 |
| C | Hand computation in ℝ[Q₈] | 16–21 |
| D | Augmentation, involution, center | 22–25 |
| E | Left multiplication as a linear map | 26–31 |
| F | The spectrum is a Fourier transform | 32–35 |
| G | Semisimple structure | 36–39 |
| H | The group determinant, and one quadratic form that explains everything | 40–43 |
| I | Build the isomorphism ℂ[D₄] ≅ ℂ[Q₈] | 44 (a–f) |
| J | Group rings over a Galois field: cyclic codes | 45–48 |
| K | Capstone: Gauss sums, cyclotomy, quadratic reciprocity | 49 (a–g) |
| L | The corridor: group rings → Laplacians → manifolds and harmonics | 50–54 |

Sections A–D are chapter-opener exercises: definitions, the convolution formula, and enough
hand computation in ℝ[D₄] and ℝ[Q₈] to make the multiplication rule automatic. Everything
after that is the payoff — the same formalism produces the Hamming code, Euler's four-square
identity, quadratic reciprocity, and the decomposition of L²(S²).

Conventions: `D_n` is the symmetry group of the *n*-gon, of order 2n — so **D₄ is the group of
the square, order 8**, and D₃ ≅ S₃. Dummit & Foote index by order and call this same group D₈;
halve every subscript if you are reading along in it. Note that D₄ and Q₈ both have order 8
despite the subscripts, since the two families count different things. The element of Q₈
usually written −1 is called `z` throughout, for reasons problem 16 explains.

## Prerequisites

A first course in abstract algebra. Linear algebra. For sections K and L, some comfort with
Galois theory and with Fourier series helps, but each is introduced from the group-ring side.

Self-contained single HTML file, no dependencies, no build step.
