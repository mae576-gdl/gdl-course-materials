## Lecture 5: Group Convolution and Steerable Filters

This notebook accompanies Lecture 5 and turns the structural arguments
from the slides into executable demonstrations.

You can:

- Derive group convolution from equivariance numerically
- Verify the kernel constraint for nontrivial representations
- Visualize steerable basis filters
- See how rotating a filter corresponds to mixing basis coefficients
- Compare naive rotation of filters with representation-driven steering

You are *not* expected to memorize the code.  
Focus on:

- How equivariance constrains kernel values
- Why admissible kernels form a linear subspace
- How representation theory couples filter values across the group
- Why steerability reduces learning to coefficient selection

---

## Environment setup (recommended)

We provide a Conda environment for local execution.

```bash
conda env create -f environment.yml
conda activate gdl
```
If you already created the environment for previous lectures, update it:
```bash
conda env update -f environment.yml
```
If you prefer not to install anything locally, you can run
all lecture notebooks directly in Colab using the badge.

### Run in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/mae576-gdl/gdl-course-materials/blob/main/lectures/lecture05/lecture05_group_convolution_and_steerable_filters.ipynb
)
