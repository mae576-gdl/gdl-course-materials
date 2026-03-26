# Lecture 9 Companion Notebook

This companion notebook provides an interactive, visual walkthrough of Euclidean equivariance in physical systems. Rather than focusing on long derivations, it uses compact 2D experiments to build intuition for how scalar and vector fields transform under rotation, and how geometry constrains the form of admissible kernels.

You will see four canonical local kernel types (scalar→scalar, scalar→vector, vector→scalar, and vector→vector), along with counterexamples that fail rotation consistency. The goal is to make the lecture language concrete: valid operators are determined by intrinsic geometric quantities (relative displacement, distances, directions, and admissible pairings), not arbitrary design choices.

## Learning goals

After running the notebook, you should be able to:

- explain why scalar channels use the trivial representation under rotation;
- explain why vector channels use the standard representation;
- interpret the geometric meaning of the four canonical kernel forms;
- identify invalid rules that introduce forbidden preferred directions or coordinate dependence;
- connect spatial and spectral viewpoints through rotation of displacement and frequency vectors.

## Setup and launch

From the repository root:

```bash
conda env create -f lectures/lecture_9/environment.yml
conda activate gdl
jupyter notebook lectures/lecture_9/lecture_9_companion.ipynb
```

This notebook is a conceptual companion to Lecture 9, not a graded assignment. Use it to experiment, visualize, and build intuition before (or after) working through formal lecture notes.
