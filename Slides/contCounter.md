If you want to count continuously with *enumerate* between two slides, you can realize it like this:

```
\begin{frame}
  \begin{enumerate}
    \item This number is 1.
    \item This number is 2.
  \end{enumerate}
\end{frame}

\begin{frame}
  \begin{enumerate}
    \setcounter{enumi}{2}
    \item This number is 3.
  \end{frame}
\end{frame}
```
