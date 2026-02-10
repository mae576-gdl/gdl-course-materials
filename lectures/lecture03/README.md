## Lecture 3: From Symmetry to Constraint

This notebook accompanies **Lecture 3** and makes precise the idea that  
**symmetry does not just describe data — it restricts which functions are allowed.**

The notebook turns the equivariance conditions from the slides into
explicit algebraic and numerical constraints that you can inspect and test.

You can:
- run it top-to-bottom during or after lecture
- project arbitrary linear maps onto symmetry-respecting ones
- visualize how symmetry collapses degrees of freedom
- see translation equivariance turn dense maps into convolutions
- explore (interactively) how symmetry improves sample efficiency

You are *not* expected to understand every line yet.  
Focus on:
- what changes when symmetry is enforced
- how constraints emerge automatically from equivariance
- why architectural structure is a consequence, not a design choice

### Environment setup (recommended)

We provide a Conda environment for local execution.

```bash
conda env create -f environment.yml
conda activate gdl
```

If you prefer not to install anything locally, you can run
all lecture notebooks directly in Colab using the badge.

### Run in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/mae576-gdl/gdl-course-materials/blob/main/lectures/lecture03/lecture03_symmetry_to_constraint.ipynb
)