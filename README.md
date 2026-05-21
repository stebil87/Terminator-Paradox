# Terminator-Paradox
# Computational Validation of "The Terminator Paradox"

This repository contains a FAIR, fully generic Python implementation of backward induction for finite extensive-form games with perfect information. The code reproduces all computational experiments described in the paper *The Terminator Paradox: When Optimal Strategies Destroy Their Own Foundations*, including:

- the simplified Terminator game,
- the four-node centipede game,
- the endogenous game tree illustrating self-invalidating equilibria.

The implementation is model-agnostic: no game-specific logic is hard-coded, and the same algorithm solves all examples by operating directly on the game-tree structure. This ensures full transparency, reproducibility, and alignment with FAIR research principles.
