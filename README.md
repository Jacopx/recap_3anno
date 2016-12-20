# Recap 3th Years
Recap of the 3th years of Politecnico di Torino (Computer Engineer) written in LaTex.

### Useful tips
Bold: ``` \textbf{...} ```
Italic: ``` \textit{...} ```
2 Graphics one line:
```
\begin{figure}[!hp]
  \centering
  \begin{minipage}{.3\textwidth}
    \centering
    \includegraphics[width=\linewidth]{images/*.png}
    \caption{...}
    \label{fig:...}
  \end{minipage}\hfill
  \begin{minipage}{.3\textwidth}
    \centering
    \includegraphics[width=\linewidth]{images/*.png}
    \caption{...}
    \label{fig:...}
  \end{minipage}\hfill
  \begin{minipage}{.3\textwidth}
    \centering
    \includegraphics[width=\linewidth]{images/*.png}
    \caption{...}
    \label{fig:...}
  \end{minipage}
\end{figure}
```
List:
```
\begin{itemize}
  \item
\end{itemize}
```
List of number:
```
\begin{enumerate}
  \item
\end{enumerate}
```
Table:
```
\begin{center}
  \begin{tabular}{ |c|c|c| }
    \hline
    Column1 & Column2 & Column3 \\
    \hline
    \hline
    cell4 & cell5 & cell6 \\
    \hline
    cell7 & cell8 & cell9 \\
    \hline
  \end{tabular}
\end{center}
```
