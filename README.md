<!-- Copyright (c) 2026 Benjamin Stanley Frohman. Licensed under Apache-2.0. -->
# CubicFourfold

**Author:** Benjamin Stanley Frohman ([@BenFrohman](https://github.com/BenFrohman), ORCID: [0009-0006-7068-3718](https://orcid.org/0009-0006-7068-3718))  
**Published Zenodo DOI:** [10.5281/zenodo.23125636](https://doi.org/10.5281/zenodo.23125636) (Concept DOI: [10.5281/zenodo.23125635](https://doi.org/10.5281/zenodo.23125635))  
**License:** Apache-2.0

This repository is **not** a proof of the general Hodge conjecture.
It records the *known* classical theorem of Zucker (1977) and Beauville–Donagi (1985) for smooth cubic fourfolds in $\mathbb{P}^5$ via the Fano variety of lines.

## What this records

A smooth cubic fourfold $X \subset \mathbb{P}^5$ has middle Hodge numbers

$$h^{4,0}=0,\quad h^{3,1}=1,\quad h^{2,2}=21,\quad h^{1,3}=1,\quad h^{0,4}=0 \qquad (b_4 = 23).$$

The rational Hodge conjecture for every such $X$ is a classical theorem of Zucker (1977), proved via the Fano variety of lines $F(X)$ and the incidence correspondence (cf. Beauville–Donagi 1985).
`CubicFourfold/Basic.lean` names that classical theorem axiomatically (`zucker_hodge`) with zero `sorry`. It does not replay the geometric construction and does not claim a new proof of the general fourfold Hodge conjecture.

A *very general* cubic still has rational Hodge lattice $\mathrm{Hdg}^2(X) = \mathbb{Q} h^2$.
Special cubics (Hassett divisors) can have extra algebraic $(2,2)$ classes; those extra classes are still algebraic by Zucker's theorem, which is distinct from high-degree Noether–Lefschetz vanishing.

## What this is not

- Not [BenFrohman/NoetherLefschetz](https://github.com/BenFrohman/NoetherLefschetz) ($d \ge 6$, no extra class).
- Not [BenFrohman/FermatPlanes](https://github.com/BenFrohman/FermatPlanes) (easy arrow on the Fermat quartic).
- Not [BenFrohman/HODGE](https://github.com/BenFrohman/HODGE) `HodgeConjecture.general_fourfold` (open extra-class fourfold).
- Not a `CycleSection` for general projective fourfolds.
- Not a Clay Millennium Prize claim.
