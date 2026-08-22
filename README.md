# The Price of Obliviousness in Noisy Linear Reconstruction

## Abstract

An unknown point $x^\star\in\mathbb{R}^d$ is queried through unit linear functionals,
each answered with adversarial additive error at most $\delta$. Recent work
determined the adaptive minimax error. Its excess above the infinite-query
Jung limit $J_d\delta=\sqrt{2d/(d+1)}\\,\delta$ vanishes doubly exponentially in
the number of queries, and it left the nonadaptive game open. We characterize
that game. For every fixed $d\geq2$, its minimax excess is
$\Theta_d(\delta T^{-2/(d-1)})$. Thus adaptivity changes the convergence law
from polynomial to doubly exponential. We also resolve the previously open
exponential-budget regime in high dimension. If
$\log T/d\to\alpha\in(0,\infty)$, then the nonadaptive minimax error satisfies

$$\frac{\mathrm{OPT}^{\mathrm{na}}_d(T,\delta)}{\delta}
 \longrightarrow \sqrt{\frac{2}{1-e^{-2\alpha}}}.$$

The upper bounds combine spherical coverings with Jung's theorem. The lower
bounds use a common transcript that hides every vertex of a suitably rotated
and expanded regular simplex. This construction is what makes classical
spherical-cap geometry sharp for point reconstruction. Finally, a batched
strategy shows that each additional adaptive batch can double the polynomial
exponent, interpolating between the two convergence laws.

## Keywords

nonadaptive queries, adversarial noise, linear queries, adaptivity gap, Jung's theorem, query complexity

## Files

- `main.pdf`
- `main.tex`
- `references.bib`
- `iclr2027_conference.sty`, `iclr2027_conference.bst`, `natbib.sty`, `fancyhdr.sty`
- `main.pdf.ots`, `README.md.ots` OpenTimestamps priority proofs

## Versions

`main.pdf` is the current version and the one to read. `main_old_2026-08-13.pdf` is
the file as first published on 2026-08-13, kept only so that its OpenTimestamps
proof stays independently verifiable:

```
ots verify main_old_2026-08-13.pdf.ots
```

The two differ by a corrected bibliography entry. The mathematics is unchanged.
`README_old_2026-08-13.md` is likewise the README as first published, kept for the
same reason.
