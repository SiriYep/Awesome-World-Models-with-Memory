# Contributing

We welcome suggestions, paper updates, and contributions of any kind! Feel free to *open issues* or *create pull requests*.

## Adding New Papers

One common contribution is adding new papers to the existing list. In this case, modify the README.md and follow the format with logos/badges:

```markdown
- [**YEAR**] **Short Title**, "Full Title". [![arXiv](https://img.shields.io/badge/arXiv-XXXX.XXXXX-b31b1b.svg)](https://arxiv.org/abs/XXXX.XXXXX) [![Website](https://img.shields.io/badge/Website-Link-blue)](link) [![Code](https://img.shields.io/badge/Code-GitHub-green)](link)
  > Brief description of the memory mechanism used.
```

### Badge Colors Guide

- **arXiv**: Red `b31b1b` - [![arXiv](https://img.shields.io/badge/arXiv-2XXX.XXXXX-b31b1b.svg)](#)
- **OpenReview**: Purple `8E44AD` - [![OpenReview](https://img.shields.io/badge/OpenReview-Paper-8E44AD.svg)](#)
- **Website**: Blue - [![Website](https://img.shields.io/badge/Website-Link-blue)](#)
- **Code**: Green - [![Code](https://img.shields.io/badge/Code-GitHub-green)](#)
- **Blog**: Orange - [![Blog](https://img.shields.io/badge/Blog-Link-orange)](#)

### Memory Mechanism Categories

When adding a paper, place it in one of the seven categories based on the primary memory mechanism:

1. **External Explicit Memory Modules** -- Memory Bank / Cache with retrieval and update
2. **Memory Compression & Retrieval** -- Fixed-budget compression, packing, hierarchical summarization
3. **Differentiable Neural Storage & Hidden State** -- RNN/LSTM/SSM persistent internal states
4. **Attention / Transformer Extensions** -- Sparse attention, KV-cache compression, long-context routing
5. **Geometric / Spatial Memory** -- Point cloud / surfel / local anchors as 3D spatial memory
6. **Training Stability & Anti-drift** -- Forcing, self-distillation, cycle consistency
7. **Benchmarks & Evaluation** -- Datasets and metrics for memory consistency

### Recommended Guidelines

- Use arXiv links rather than custom links where possible, linking to the *abstract* not PDF
- Include all available resources (Paper/Website/Code) with corresponding badges
- Papers within each section are ordered chronologically (older first, newer at the end)
- Include a brief `>` blockquote description of the memory mechanism after each entry
- If a paper spans multiple categories, place it in the primary one and mention secondary mechanisms in the description
