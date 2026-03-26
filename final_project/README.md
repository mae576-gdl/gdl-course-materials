## Final Project: Experimental Best Practices Notebook

This notebook is the final-project guide for the course.

It now combines **brief conceptual guidance** with **small executable demonstration cells** so students can see how to implement key ideas directly in notebook form.

Demonstrations include:

- Fair baseline comparison via parameter matching (toy PyTorch models)
- IID vs structured/OOD split design
- Sample-efficiency summaries across training set sizes
- Multi-seed reporting with mean ± std
- Equivariance consistency checks
- Worked mini examples for rotation-equivariant images, permutation-equivariant graphs, and 3D geometric prediction

The goal is pedagogical scaffolding for project design, not a full production training pipeline.

---

## Environment setup

```bash
conda env create -f environment.yml
conda activate gdl
```

If you already have the course environment, update it:

```bash
conda env update -f environment.yml
```
