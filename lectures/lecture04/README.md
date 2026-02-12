## Lecture 4: Representations and Feature Geometry

This notebook accompanies Lecture 4 and turns the structural arguments
from the slides into executable demonstrations.

You can:

- Verify that change of basis conjugates a representation
- See that ReLU commutes with translation but breaks rotation
- Numerically project a linear map onto the translation-equivariant subspace
- Observe convolution emerge from symmetry
- Confirm that pooling produces invariance

You are *not* expected to memorize the code.
Focus on:

- What properties hold automatically
- What breaks when compatibility is violated
- How symmetry restricts structure

---

## Environment setup (recommended)

We provide a Conda environment for local execution.

```bash
conda env create -f environment.yml
conda activate gdl
```
If you already created the environment for previous lectures, update it:
```
conda env update -f environment.yml
```
If you prefer not to install anything locally, you can run
all lecture notebooks directly in Colab using the badge.

### Run in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/mae576-gdl/gdl-course-materials/blob/main/lectures/lecture04/lecture04_representations_and_feature_geometry.ipynb
)

