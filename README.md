# Polynomial Optimization Without Derivatives

This repository contains academic documents describing methods for finding local extrema of polynomials without computing derivatives.

## Contents

- `polynomial_optimization_wo_derivatives_ru.tex` - Original Russian document (available on main branch)
- `polynomial_optimization_wo_derivatives_ru.pdf` - Compiled Russian PDF (available on main branch)  
- `powder_2_tricks_en.tex` - English translation

## Methods Described

### Method 1: Method of Means for Finding Extrema
Invented by Gleb Veselsky in August 2024, this method uses the arithmetic-geometric mean inequality by selecting additional factors. Works for polynomials of any degree factored into linear factors.

### Method 2: Johann Hudde's Method with Arithmetic Progressions
A 17th century method by Johann Hudde (mathematician and mayor of Amsterdam) that identifies multiple roots by multiplying polynomial coefficients by arithmetic progressions.

## Key Features

- **Derivative-free**: No gradient computation required
- **Historical significance**: Includes both modern (2024) and classical (17th century) approaches  
- **Mathematical rigor**: Complete proofs and theoretical foundations
- **Practical examples**: Multiple worked examples with varying complexity

## Examples Include

- Simple cases: $f(x) = x^2 \cdot (6 - 2x)$ and $f(x) = x^{10}(5-x)$ 
- Complex cases: $f(x) = x(x+1)(2-x)$ and rational functions
- Tangent finding and multiple root identification

## Compilation

To compile the English LaTeX document:

```bash
xelatex powder_2_tricks_en.tex
```

The Russian original requires biber for bibliography:
```bash
xelatex polynomial_optimization_wo_derivatives_ru.tex
biber polynomial_optimization_wo_derivatives_ru
xelatex polynomial_optimization_wo_derivatives_ru.tex
```

## Author

B. Demeshev

## License

This work is licensed under CC0-1.0 Universal (Creative Commons Zero v1.0 Universal).
