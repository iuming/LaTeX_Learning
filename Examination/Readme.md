# LaTeX Examination

## 第1题 
```tex
\documentclass{article}
\usepackage{graphicx}
\usepackage{subfigure}

\begin{document}

\begin{figure}
    \centering
    \subfigure[123]{\includegraphics[width=0.45\textwidth]{Fig/exph}\label{fig:exph}}
    \subfigure[456]{\includegraphics[width=0.45\textwidth]{Fig/exgr}\label{fig:exgr}}

    \subfigure[123]{\includegraphics[width=0.45\textwidth]{Fig/exph}\label{fig:exph}}
    \subfigure[456]{\includegraphics[width=0.45\textwidth]{Fig/exgr}\label{fig:exgr}}

    \subfigure[123]{\includegraphics[width=0.45\textwidth]{Fig/exph}\label{fig:exph}}
    \subfigure[456]{\includegraphics[width=0.45\textwidth]{Fig/exgr}\label{fig:exgr}}
    \caption{Second caption}
    \label{fig:exph,exgr}
\end{figure}

\end{document}

```

## 第2题 
```tex
\documentclass{article}
\usepackage{graphicx}
\graphicspath{ {images/} }

\begin{document}
The universe is immense and it seems to be homogeneous,
in a large scale, everywhere we look at.

\includegraphics{universe}

There's a picture of a galaxy above
\end{document}
```

## 第3题 
```tex
\documentclass[12pt, letterpaper, twoside]{article}
\usepackage[utf8]{inputenc}

\begin{document}
    Some of the \textbf{greatest}
    discoveries in \underline{science} 
    were made by \textbf{\textit{accident}}.

    Some of the greatest \emph{discoveries} 
    in science 
    were made by accident.

    \textit{Some of the greatest \emph{discoveries} 
    in science 
    were made by accident.}

    \textbf{Some of the greatest \emph{discoveries} 
    in science 
    were made by accident.}
\end{document}
```

第4题
```
\documentclass{article}
\usepackage{ctex}
\usepackage{graphicx}
\usepackage{amsmath}
\usepackage{cite}

\title{郭凯}
\begin{document}
\maketitle
\begin{equation}
    \begin{matrix}
        a_{11} & a_{12} & a_{13} \\
        a_{11} & a_{12} & a_{13}
    \end{matrix}
\end{equation}
\begin{figure}[htbp]
    \includegraphics[width=1.0\textwidth]{Elec-MuonHydrogen.png}
\end{figure}
2244434321
4321432143214\cite{李旭斌2012试论我国工伤赔偿法律制度之完善——以建筑行业农民工为考察对象}
\bibliographystyle{plain}
\bibliography{references.bib}
\end{document}
```