# JSP-000506 — Random graph χ vs χ_b (Petkov + GPT-5.6 2026 stronger lower bound)

## Problem
In a random graph G(n, 1/2), how much smaller than the chromatic number is
the minimum number of parts in a partition into cliques and independent sets
(χ_b(G), the biclique partition number, or equivalently 1/clique cover number)?

Reference: Petkov and GPT-5.6 (2026), stronger lower bound.

## Status
JSP catalog notes that the original bounty ($1000) was claimed by the
Petkov+GPT-5.6 paper contribution; Lean proof is still open.  This
scaffold sets up the abstract, finite-carrier version using `Finset ℕ`
as the vertex set, with the main theorem left as `sorry`.

## Build
```
cd D:\evox-main\JustinSunPrize\jsp-506-ramsey-partition
lake build
```