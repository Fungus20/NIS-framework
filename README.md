# NIS Framework

**Nested Integral Structure (NIS)**  
A dynamical-system framework based on variable-limit integral iteration, with convergence analysis, failure boundaries, and error estimates.

This repository contains the manuscript for the Nested Integral Structure (NIS) model.

## Paper

- Chinese manuscript: [`NIS(CN).md`](./NIS(CN).md)
- English manuscript: [`NIS(EN).md`](./NIS(EN).md)
- LaTeX source: [`NIS.tex`](./NIS.tex)
- PDF: [`NIS.pdf`](./NIS.pdf)

> The preprint has been (or will be) submitted to Preprints.org.

## Core Idea

The basic iteration takes the form

\[ I_{n+1} = \int_{L(I_n)}^{U(I_n)} f(t)\, dt \]

where the integration bounds at each step are determined by the numerical output of the preceding step.

## Repository Contents

| File | Description |
|------|-------------|
| `NIS(CN).md` | Full manuscript (Chinese) |
| `NIS(EN).md` | Full manuscript (English) |
| `NIS.tex` | LaTeX source |
| `NIS.pdf` | Compiled PDF |
| `NIS.jpg` | Graphical abstract |
| `LICENSE` | MIT License |

## Main Results

1. **Theorem 4.1**: Sufficient conditions for convergence under eventually uniformly Lipschitz compression and consecutive perturbation summability
2. **Failure boundaries**: Explicit counterexamples (e.g. \(F(x)=x^2\), \(F(x)=\sin x\))
3. **Error analysis**: Propagation bounds of the form \(\delta/(1-q)\), including finite-\(n\) estimates

## Contact

- Author: Zhenhao Gao
- Email: mja963373@gmail.com
- ORCID: https://orcid.org/0009-0002-3762-9913

## License

This project is licensed under the MIT License — see the [LICENSE](./LICENSE) file for details.

---

*The mathematical framework and core conclusions were proposed by the author. AI tools were used for language polishing, formatting, and multi-round cross-review. The author is responsible for the final content.*
