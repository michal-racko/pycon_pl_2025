# Monte Carlo Methods for Optimization - PyCon PL 2025

This repository contains Jupyter notebooks demonstrating Monte Carlo methods applied to various optimization and modeling problems.

## Notebooks

### 001-pi-estimation.ipynb
Demonstrates basic Monte Carlo principles through π estimation using geometric probability. Shows random sampling convergence and uncertainty quantification using the unit circle method.

### 002-snp500-price.ipynb
Financial modeling using Monte Carlo methods for S&P 500 price prediction. Implements triple Gaussian mixture distributions and Russian Roulette variance reduction techniques.

### 003-travelling-salesman.ipynb
Combinatorial optimization using Simulated Annealing for the Travelling Salesman Problem. Compares greedy algorithms with Monte Carlo metaheuristics for finding optimal city routes.

## Building the Presentation

The LaTeX presentation is located in the `presentation/` directory. To build the PDF:

```bash
cd presentation
pdflatex main.tex
```

Note: You may need to run the command twice to resolve all references and generate the table of contents properly.

## Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```