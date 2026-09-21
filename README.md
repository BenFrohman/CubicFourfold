# CubicFourfold

Author of this record: Benjamin Stanley Frohman ([@BenFrohman](https://github.com/BenFrohman)).
Copyright (c) 2026 Benjamin Stanley Frohman. Apache-2.0.

This repository is **not** a proof of the Hodge conjecture.
It records the *known* case of Hodge for cubic fourfolds in P^5.

## What this records

A smooth cubic fourfold `X subset P^5` has middle Hodge numbers

    h^{4,0}=0, h^{3,1}=1, h^{2,2}=21, h^{1,3}=1, h^{0,4}=0
    (b_4 = 23).

Hodge for every such `X` is a theorem of Zucker (1977), via the Fano variety of lines.
`CubicFourfold/Basic.lean` names that theorem as an axiom. It does not replay the proof.
There is no `sorry`.

A *very general* cubic still has rational Hodge lattice `Hdg^2 = Q h^2`.
Special cubics (Hassett) can have extra algebraic classes. Those extra classes are
still algebraic; that is part of Zucker’s theorem, not Noether–Lefschetz.

## What this is not

- Not [BenFrohman/NoetherLefschetz](https://github.com/BenFrohman/NoetherLefschetz) (`d ≥ 6`, no extra class).
- Not [BenFrohman/FermatPlanes](https://github.com/BenFrohman/FermatPlanes) (easy arrow on Fermat quartic).
- Not [BenFrohman/HODGE](https://github.com/BenFrohman/HODGE) `HodgeConjecture.general_fourfold` (open extra-class fourfold).
- Not a `CycleSection`.
- Not a Clay prize claim.
