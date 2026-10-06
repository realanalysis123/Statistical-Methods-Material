# Statistical Methods Course Materials

A collection of notes, worked examples, and practice problems for the **Statistical Methods** course. This repository is meant to be a clean, easy-to-access study resource that can grow over time.

![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

---

## Table of Contents

- [About](#about)
- [Topics Covered](#topics-covered)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)


---

## About

This repository contains Statistical Methods material organized topic by topic. Each topic typically includes:

- a summary of key concepts and formulas,
- worked examples with solutions,
- practice problems,
- (optional) R/Python code for hands-on practice and visualization.

It is intended for students taking a Statistical Methods course, as well as anyone who wants to review the fundamentals of statistical inference.

## Topics Covered

> Adjust this list to match the material you actually upload.

| No | Topic | Description |
|----|-------|-------------|
| 1 | Descriptive Statistics | Measures of center and spread, data presentation |
| 2 | Probability and Random Variables | Probability concepts, expected value, variance |
| 3 | Probability Distributions | Binomial, Poisson, Normal, and other distributions |
| 4 | Sampling Distributions | Central Limit Theorem, $t$, $\chi^2$, and $F$ distributions |
| 5 | Parameter Estimation | Point estimates and confidence intervals |
| 6 | Hypothesis Testing | One- and two-sample tests, Type I and Type II errors |
| 7 | Analysis of Variance (ANOVA) | One-way designs and multiple comparisons |
| 8 | Regression and Correlation | Simple linear regression and correlation coefficients |
| 9 | Nonparametric Statistics | Sign test, Wilcoxon, Kruskal-Wallis, and related tests |

## Repository Structure

> Adjust this to match your repository.

```
statistical-methods/
├── README.md
├── LICENSE
├── 01-descriptive-statistics/
│   ├── notes.pdf
│   ├── exercises.pdf
│   └── code/
├── 02-probability-random-variables/
├── 03-probability-distributions/
├── ...
├── data/            # datasets used in examples and exercises
└── assets/          # images and logos
```

## Getting Started

**1. Clone the repository**

```bash
git clone https://github.com/realanalysis123/statistical-methods.git
cd statistical-methods
```

**2. Open the materials**

- **PDF** files can be opened or downloaded directly from each topic folder.
- **`.tex`** files (if included) can be compiled with LaTeX, for example:

  ```bash
  pdflatex notes.tex
  ```

  Or upload the folder to [Overleaf](https://www.overleaf.com).

**3. Run the practice code (if included)**

- **R** code: open the `.R` or `.Rmd` files in RStudio.
- **Python** code: install the required packages with

  ```bash
  pip install -r requirements.txt
  ```

## Contributing

Feedback is very welcome, whether it is a typo fix, a better explanation, or additional problems.

1. Fork this repository.
2. Create a new branch: `git checkout -b fix-topic-x`.
3. Commit your changes: `git commit -m "Fix formula in topic X"`.
4. Push to the branch: `git push origin fix-topic-x`.
5. Open a Pull Request.

If you find a mistake but do not have time to fix it, please open an **Issue**.

## License

The contents of this repository are released under the **MIT License** (see the `LICENSE` file). You are free to use and modify the material for learning purposes with attribution. Change the license if you prefer, for example CC BY 4.0 for non-code material.

## Author

**Kristian Aga Yudistira Laru**
Statistics and Data Science student, IPB University

- GitHub: [@realanalysis123](https://github.com/realanalysis123)
- Kaggle: [krisstiann](https://www.kaggle.com/krisstiann)
- LinkedIn: [Kristian Aga Yudistira Laru](https://www.linkedin.com/in/kristian-aga-yudistira-laru-a9921b34a)

---

*If you find this repository useful, consider giving it a star ⭐ on GitHub.*
