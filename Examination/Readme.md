# LaTeX Examination

```tex
\documentclass[aps,prd,showpacs,superscriptaddress,preprintnumbers]{revtex4}

\usepackage{graphicx,float,wrapfig,subfigure}
\usepackage{amsfonts,amsmath,amssymb,amstext,esint}
\usepackage{latexsym}
 \usepackage{bm}
\usepackage{color}
\usepackage[normalem]{ulem}
\usepackage{booktabs}
\usepackage{makecell,multirow,longtable,rotating,diagbox}



\newbox\pippobox
\usepackage{amssymb,amsfonts}
%\usepackage{subfig}
\newcommand{\be}{\begin{equation}}
\newcommand{\ee}{\end{equation}}
\newcommand{\ba}{\begin{eqnarray}}
\newcommand{\ea}{\end{eqnarray}}
\newcommand{\diag}{\text{diag}}
\newcommand{\tr}{\,\mbox{tr}}
\newcommand{\sign}{\,\mbox{sign}}
\newcommand{\non}{\nonumber\\}
\definecolor{red}{rgb}{0.7,0,0}
\definecolor{green}{rgb}{0,0.5,0}
\newcommand{\revision}[1]{\textcolor{red}{#1}}
\newcommand{\revisionA}[1]{\textcolor{blue}{#1}}
\newcommand{\revisionB}[1]{\textcolor{green}{#1}}
\newcommand{\revisionC}[1]{\textcolor{magenta}{#1}}
%\topmargin0.0pt

\begin{document}

\title{Assessment for scientific writing}
\date{\today}

\author{Liu Ming}
\email{liuming21@mails.ucas.ac.cn}
\affiliation{Institute of High Energy Physics, Chinese Academy of Sciences}


\begin{abstract}

	{\rm The scientific writing course introduced the general IMRAD structure for scientific papers, and introduced basic skills on how to use Latex editing a
		scietific paper.}

	{\it }
\end{abstract}
\pacs{12.38.Mh,25.75.-q,11.10.Wx,13.88+e }
\maketitle



\section{Introduction}
\label{sec:equation}

Please give a brief introduction on the general structure of scientific papers here,i.e. the IMRAD structure \cite{}.  What kind of content should be addressed in each part?



\section{Equations}

Please type both differential and integral Maxwell Equations shown in Eq.(\ref{Eq.1}) and (\ref{Eq.2}).
The integral Maxwell Equations  takes the following form :
\begin{equation*}
	\text{Gauss's Law:} \qquad \qquad \oiint\limits_{\partial \Omega} \mathbf{E} \cdot \mathbf{dS} = \frac{1}{\epsilon_{0}} \iiint_{\Omega} \rho dV ,
\end{equation*}
\begin{equation*}
	\text{Gauss's Law for magnetism:} \oiint_{\partial \Omega} \mathbf{B} \cdot \mathbf{dS} = 0
\end{equation*}
\begin{equation*}
	\text{Faraday's law of induction :} \oint_{\partial \sum} \mathbf{E} \cdot \mathbf{dl} = - \frac{d}{dt} \iiint_{\sum} \mathbf{B} \cdot \mathbf{dS}
\end{equation*}
\begin{equation}
	\text{Ampere's law :} \oint_{\partial \sum} \mathbf{B} \cdot \mathbf{dl} = \mu_{0} (\iint_{\sum} \mathbf{J} \cdot d\mathbf{S} + \epsilon_{0}\frac{d}{dt}\iint_{\sum} \mathbf{E} \cdot d\mathbf{S}) .
	\label{Eq.1}
\end{equation}

The differential Maxwell Equations  takes the following form:
\begin{equation*}
	\text{Gauss's Law:} \qquad \qquad \bigtriangledown \cdot \mathbf{E} = \frac{\rho}{\epsilon_{0}} ,
\end{equation*}
\begin{equation*}
	\text{Gauss's Law for magnetism:} \bigtriangleup \cdot \mathbf{B} = 0
\end{equation*}
\begin{equation*}
	\text{Faraday's law of induction :} \bigtriangledown \times \mathbf{E} = - \frac{\partial \mathbf{B}}{\partial t}
\end{equation*}
\begin{equation}
	\text{Ampere's law :} \bigtriangledown \times \mathbf{B} = \mu_{0} (\mathbf{J} + \epsilon_{0}\frac{\partial \mathbf{E}}{\partial t}) .
	\label{Eq.2}
\end{equation}


Please type Eq.(\ref{}) shown in test0103original.pdf file.


\section{Figures}

Use subfigure to insert two subfigures ${\rm Divergence\_theorem\_in\_EM.png}$ and ${\rm Curl\_theorem\_in\_EM.png}$ in attachment.

\begin{figure}[!h]
	\subfigure[The Gauss divergence theorem]{\label{fig.div.sub.1}
		\includegraphics[width=6cm]{Divergence_theorem_in_EM.png}}
	\subfigure[The Kelvin–Stokes theorem]{\label{fig.curl.sub.2}
		\includegraphics[width=6cm]{Curl_theorem_in_EM.png}}
	\caption{The Gauss divergence theorem and the Kelvin-Stokes theorem}
	\label{fig:quarkmass}
\end{figure}

\section{Tables}
\label{sec:introduction}

In this section, please make Table \ref{} as shown in test0103original.pdf file.

Please make Table \ref{} here.

\vskip 2cm







\vskip 2cm



\section{list 10 references}

Please list 10 references from [2]-[10] shown in test0103original.pdf file.



\begin{thebibliography}{99}

	\bibitem{SW}Michael Alley, The craft of sscientific writing, Springer;1996





\end{thebibliography}

\end{document}



```