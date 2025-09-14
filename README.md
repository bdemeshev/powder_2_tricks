# POWDER: 2 Tricks for Polynomial Optimization Without Derivatives

This repository contains academic documents describing two efficient methods for optimizing polynomial functions without using derivatives.

## Contents

- `powder_2_tricks_ru.tex` - Russian version of the paper
- `powder_2_tricks_en.tex` - English translation of the paper

## Methods Described

### Trick 1: Golden Section Method for Polynomials
Adapts the classical golden section method for polynomial functions, utilizing the unimodality property and ensuring linear convergence O(φ^-n).

### Trick 2: Polynomial Interpolation with Adaptive Node Selection
Uses strategic interpolation with lower-degree polynomials and Chebyshev nodes to analytically find extremums.

## Key Features

- **Derivative-free**: No gradient computation required
- **Numerically stable**: Robust convergence properties
- **Practical**: Tested on polynomials up to degree 8
- **Applications**: Useful for noisy data and discrete functions

## Compilation

To compile the LaTeX documents:

```bash
pdflatex powder_2_tricks_ru.tex
pdflatex powder_2_tricks_en.tex
```

## Author

B. Demeshev

## License

This work is licensed under CC0-1.0 Universal (Creative Commons Zero v1.0 Universal).
