# Figures Directory

This directory contains TikZ diagrams extracted from the section files for better organization and reusability.

## Naming Convention

Figures are named using the pattern: `{section-number}-{descriptive-name}.tex`

For example:
- `03-vector-basis-example.tex` - From section 3 (Vectors)
- `04-covector-lines.tex` - From section 4 (Covectors)

## Usage

In your section files, include figures using:
```latex
\begin{center}
\input{figures/figure-name}
\end{center}
```

Or for side-by-side figures:
```latex
\begin{center}
\begin{minipage}[t]{0.48\linewidth}
\centering
\input{figures/figure-1}
\end{minipage}
\hfill
\begin{minipage}[t]{0.48\linewidth}
\centering
\input{figures/figure-2}
\end{minipage}
\end{center}
```

## Current Figures

### Section 3: Vectors
- `03-vector-basis-example.tex` - Example showing vector in two basis systems
- `03-forward-transformation.tex` - Forward basis transformation diagram
- `03-backward-transformation.tex` - Backward basis transformation diagram
- `03-vector-scaling-old-basis.tex` - Vector in original scaled basis
- `03-vector-scaling-new-basis.tex` - Vector in upscaled basis
- `03-vector-rotation-old-basis.tex` - Vector in original basis
- `03-vector-rotation-new-basis.tex` - Vector in rotated basis

### Section 4: Covectors
- `04-covector-lines.tex` - Covector visualization as level sets
- `04-covector-beta.tex` - Beta covector visualization
- `04-covector-gamma.tex` - Gamma covector visualization
- `04-covector-sum.tex` - Sum of beta and gamma covectors
- `04-epsilon1-basis.tex` - Epsilon^1 dual basis covector
- `04-epsilon2-basis.tex` - Epsilon^2 dual basis covector
- `04-alpha-covector.tex` - Generic alpha covector with basis vectors
- `04-dual-basis-decomposition.tex` - Decomposition of alpha into dual basis
- `04-basis-vectors-example.tex` - Basis vectors for coordinate transformation example
