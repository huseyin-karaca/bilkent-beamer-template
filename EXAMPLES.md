# Quick Examples

## Basic Frame Structure

### Centered Content
```latex
\begin{frame}[c]{Title}
    Content here
\end{frame}
```

### Top-aligned Content
```latex
\begin{frame}[t]{Title}
    Content here
\end{frame}
```

### Bottom-aligned with References
```latex
\begin{frame}[b]{Title}
    Content here
    
    \vfill 
    \hrule
    \vspace{0.1cm}
    \tiny
    \textbf{References:} \\
    {[1]} Author et al., ``Title,'' \textit{Venue}, Year.
\end{frame}
```

## Blocks

### Regular Block
```latex
\begin{block}{Block Title}
    Content
\end{block}
```

### Alert Block (Red)
```latex
\begin{alertblock}{Important}
    Critical information
\end{alertblock}
```

### Example Block (Green)
```latex
\begin{exampleblock}{Example}
    Example content
\end{exampleblock}
```

## Columns

### Two Columns
```latex
\begin{columns}[c]
    \begin{column}{0.48\textwidth}
        Left content
    \end{column}
    \begin{column}{0.48\textwidth}
        Right content
    \end{column}
\end{columns}
```

### Three Columns
```latex
\begin{columns}[t]
    \begin{column}{0.32\textwidth}
        Column 1
    \end{column}
    \begin{column}{0.32\textwidth}
        Column 2
    \end{column}
    \begin{column}{0.32\textwidth}
        Column 3
    \end{column}
\end{columns}
```

## Tables

```latex
\begin{table}[t]
\centering
\begin{tabular}{l|cc}
\toprule
\textbf{Item} & \textbf{Col 1} & \textbf{Col 2} \\
\midrule
Row 1 & 0.85 & 0.92 \\
Row 2 & 0.88 & 0.95 \\
\bottomrule
\end{tabular}
\caption{Your caption here}
\end{table}
```

## Colors

Available theme colors:
- `\textcolor{pantonereflectblue}{Blue text}`
- `\textcolor{flagred}{Red text}`

## Images

```latex
\begin{figure}
    \centering
    \includegraphics[width=0.8\textwidth]{filename.pdf}
    \caption{Figure caption}
    \label{fig:label}
\end{figure}
```

