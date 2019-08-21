# Beamer

```tex
% animation
\begin{frame}\transblindshorizontal<1> % 配置动画
\frametitle{\textsc{Preface}} % frame配置页标题
\begin{itemize}
    \item\hilite<1> {\bf Prerequisites:} % 配hilite置先后级别
    \begin{itemize}
        \item mechanics
        \item Electrodynamics
    \end{itemize}\pause % 配置暂停
    \item\hilite<2> {\bf TextBook:}
    \begin{itemize}
        \item mechanics
        \item Electrodynamics
    \end{itemize}\pause
\end{itemize}
```

latex生成的pdf打开的时候自动全屏

```tex
\hyptersetup{pdfpagemod={FullScreen}}
```

Preview [Themes](https://hartwork.org/beamer-theme-matrix/) to choose `\usetheme{}` and `\usecolortheme{}`