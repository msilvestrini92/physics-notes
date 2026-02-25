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