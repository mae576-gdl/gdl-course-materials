## Lecture 2: Symmetry as a Design Constraint

This notebook accompanies Lecture 2 and turns the formal definitions
from the slides into executable checks.

You can:
- run it top-to-bottom during or after lecture
- modify simple transformations
- test whether a function is invariant or equivariant

You are *not* expected to understand every line yet.
Focus on:
- what properties hold automatically
- what breaks when structure is ignored
- how symmetry shows up as constraints, not heuristics

### Environment setup (recommended)

We provide a Conda environment for local execution.

```bash
conda env create -f environment.yml
conda activate gdl
