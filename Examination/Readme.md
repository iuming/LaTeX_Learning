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