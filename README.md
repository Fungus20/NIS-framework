# NIS Framework

**Nested Integral Structure (NIS)**  
A dynamical-system framework based on variable-limit integral iteration, with convergence analysis, failure boundaries, and error estimates.

This repository contains the manuscript for the NIS (Nested Integral Structure) model.

## Paper

- Chinese manuscript: [`NIS.md`](./NIS.md)

> Note: An English version is in preparation. A PDF/LaTeX release is planned for later preprint submission.

## Core Idea

The basic iteration takes the form

\[ I_{n+1} = \int_{L(I_n)}^{U(I_n)} f(t)\, dt \]

where the integration bounds at each step are determined by the numerical output of the preceding step.

## Repository Contents

| File | Description |
|------|-------------|
| `NIS.md` | Full manuscript (Chinese) |
| `LICENSE` | MIT License |

## Main Results

1. **Theorem 4.1**: Sufficient conditions for convergence under tail-uniform Lipschitz compression and consecutive perturbation summability
2. **Failure boundaries**: Explicit counterexamples (e.g. \(F(x)=x^2\), \(F(x)=\sin x\))
3. **Error analysis**: Propagation bounds of the form \(\delta/(1-q)\), including finite-\(n\) estimates

## Contact

- Author: Zhenhao Gao
- Email: mja963373@gmail.com

## License

This project is licensed under the MIT License — see the [LICENSE](./LICENSE) file for details.

---

*The mathematical framework and core conclusions were proposed by the author. AI tools were used for language polishing, formatting, and multi-round cross-review. The author is responsible for the final content.*
