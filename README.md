# TMLR Journal Template (ML-Extended)

LaTeX template for Transactions on Machine Learning Research (TMLR), extended with ML-specific packages, macros, and examples.

## Quick Start

1. Edit `main.tex` — replace placeholder content with your paper.
2. Add references to `main.bib`.
3. Compile: `pdflatex main && bibtex main && pdflatex main && pdflatex main`

## Submission Modes

| Mode | Preamble | Use |
|------|----------|-----|
| Anonymous | `\usepackage{tmlr}` | Double-blind submission |
| Accepted | `\usepackage[accepted]{tmlr}` | Camera-ready |
| Preprint | `\usepackage[preprint]{tmlr}` | arXiv upload |

## What's Included

- **Packages**: `booktabs`, `subcaption`, `algpseudocode`, `tikz`, `pgfplots`, `amsthm`, `cleveref`, `wrapfig`, `enumitem`, `multirow`, `microtype`, and more.
- **Math macros** (`math_commands.tex`): `\argmin`, `\argmax`, `\Loss`, `\norm{}`, `\expect{}`, `\reals`, `\floor{}`, `\ceil{}`, `\bigo{}`, `\convp`, etc.
- **Theorem environments**: `theorem`, `lemma`, `proposition`, `corollary`, `definition`, `assumption`, `remark`.
- **Collaboration macros**: `\todo{}`, `\authorA{}`, `\authorB{}`, `\authorC{}` (color-coded, with kill switch for final submission).
- **Examples**: results tables, ablation tables, subfigures, TikZ architecture diagrams, pgfplots training curves, pseudocode algorithms, and theorem/proof blocks.
