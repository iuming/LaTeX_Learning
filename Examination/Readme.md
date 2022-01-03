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
\usepackage{multirow}


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


Please type Eq.(\ref{Eq.3}) shown in test0103original.pdf file.
\begin{equation}
	\Phi^{\pm} =
	\begin{pmatrix}
		[\bigtriangleup_{uu}^{rr}]^{\pm} & 0                                & 0 & 0                                & [\bigtriangleup_{ud}^{rg}]^{\pm} & 0 & 0                                & 0                                & [\bigtriangleup_{us}^{rb}]^{\pm}                                    \\
		0                                & 0                                & 0 & [\bigtriangleup_{du}^{rg}]^{\pm} & 0                                & 0 & 0                                & 0                                & 0                                & 0                                \\
		0                                & 0                                & 0 & 0                                & 0                                & 0 & 0                                & [\bigtriangleup_{us}^{rb}]^{\pm} & 0                                & 0                                \\
		0                                & [\bigtriangleup_{du}^{rg}]^{\pm} & 0 & 0                                & 0                                & 0 & 0                                & 0                                & 0                                & 0                                \\
		[\bigtriangleup_{du}^{rg}]^{\pm} & 0                                & 0 & 0                                & [\bigtriangleup_{dd}^{gg}]^{\pm} & 0 & 0                                & 0                                & 0                                & [\bigtriangleup_{ds}^{gb}]^{\pm} \\
		0                                & 0                                & 0 & 0                                & 0                                & 0 & 0                                & 0                                & [\bigtriangleup_{sd}^{gb}]^{\pm} & 0                                \\
		0                                & [\bigtriangleup_{su}^{rb}]^{\pm} & 0 & 0                                & 0                                & 0 & 0                                & 0                                & 0                                & 0                                \\
		0                                & 0                                & 0 & 0                                & 0                                & 0 & [\bigtriangleup_{sd}^{gb}]^{\pm} & 0                                & 0                                & 0                                \\
		[\bigtriangleup_{us}^{rb}]^{\pm} & 0                                & 0 & 0                                & [\bigtriangleup_{ds}^{gb}]^{\pm} & 0 & 0                                & 0                                & 0                                & [\bigtriangleup_{ss}^{bb}]^{\pm} \\
	\end{pmatrix}
	\label{Eq.3}
\end{equation}

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

\begin{table}[htbp]
	\begin{tabular}{|ll|ccc|cll|}
		\hline
		\multicolumn{2}{|l|}{\multirow{2}{*}{}}                & \multicolumn{3}{c|}{Model A}    & \multicolumn{3}{c|}{Model B}                                                                                                                                                \\ \cline{3-8}
		\multicolumn{2}{|l|}{}                                 & \multicolumn{1}{l|}{$N_{TC}=3$} & \multicolumn{1}{l|}{$N_{TC}=4$}  & \multicolumn{1}{l|}{$N_{TC}=5$} & \multicolumn{1}{l|}{$N_{TC}=3$} & \multicolumn{1}{l|}{$N_{TC}=4$} & $N_{TC}=5$                         \\ \hline
		\multicolumn{1}{|l|}{\multirow{3}{*}{\textbf{Input}}}  &                                 & \multicolumn{1}{l|}{1.072}       & \multicolumn{1}{l|}{1.079}      & \multicolumn{1}{l|}{1.083}      & \multicolumn{1}{l|}{0.299}      & \multicolumn{1}{l|}{0.299} & 0.299 \\ \cline{2-8}
		\multicolumn{1}{|l|}{}                                 & c                               & \multicolumn{1}{l|}{1.395}       & \multicolumn{1}{l|}{1.141}      & \multicolumn{1}{l|}{1.423}      & \multicolumn{1}{l|}{0.099}      & \multicolumn{1}{l|}{0.099} & 0.099 \\ \cline{2-8}
		\multicolumn{1}{|l|}{}                                 & M                               & \multicolumn{1}{l|}{0.553}       & \multicolumn{1}{l|}{0.541}      & \multicolumn{1}{l|}{0.534}      & \multicolumn{1}{l|}{0.380}      & \multicolumn{1}{l|}{0.329} & 0.295 \\ \hline
		\multicolumn{1}{|l|}{\multirow{6}{*}{\textbf{Output}}} & S                               & \multicolumn{3}{c|}{0.15(fixed)} & \multicolumn{1}{l|}{0.721}      & \multicolumn{1}{l|}{0.888}      & 1.034                                                                \\ \cline{2-8}
		\multicolumn{1}{|l|}{}                                 & T(GeV)                          & \multicolumn{1}{c|}{356}         & \multicolumn{1}{c|}{358}        & 360                             & \multicolumn{3}{c|}{100(fixed)}                                      \\ \cline{2-8}
		\multicolumn{1}{|l|}{}
	\end{tabular}
\end{table}

Please make Table \ref{} here.

\vskip 2cm







\vskip 2cm



\section{list 10 references}

Please list 10 references from [2]-[10] shown in test0103original.pdf file.



\begin{thebibliography}{99}

	\bibitem{SW}Michael Alley, The craft of sscientific writing, Springer;1996
	\bibitem{KP}K. Kiuchi, P. Cerd´a-Dur´an, K. Kyutoku, Y. Sekiguchi and M. Shibata, Phys. Rev. D \textbf{92}, no. 12, 124034 (2015)doi:10.1103/PhysRevD.92.124034 [arXiv:1509.09205 [astro-ph.HE]].
	\bibitem{LL}L. Baiotti and L. Rezzolla, Rept. Prog. Phys. \textbf{80}, no. 9, 096901 (2017) doi:10.1088/1361-6633/aa67bb [arXiv:1607.03540[gr-qc]].
	\bibitem{JO}J. O. Andersen, W. R. Naylor and A. Tranberg, Rev. Mod. Phys. \textbf{88}, 025001 (2016) doi:10.1103/RevModPhys.88.025001[arXiv:1411.7176 [hep-ph]].
	\bibitem{VA}V. A. Miransky and I. A. Shovkovy, Phys. Rept. \textbf{576}, 1 (2015) doi:10.1016/j.physrep.2015.02.003 [arXiv:1503.00732 [hep-ph]].
	\bibitem{DE}D. E. Kharzeev, J. Liao, S. A. Voloshin and G. Wang, Prog. Part. Nucl. Phys. \textbf{88}, 1 (2016) doi:10.1016/j.ppnp.2016.01.001[arXiv:1511.04050 [hep-ph]].
	\bibitem{DK}D. Kharzeev and A. Zhitnitsky, Nucl. Phys. A \textbf{797}, 67 (2007). [arXiv:0706.1026 [hep-ph]].
	\bibitem{LD}D. E. Kharzeev, L. D. McLerran and H. J. Warringa, Nucl. Phys. A \textbf{803}, 227 (2008). [arXiv:0711.0950 [hep-ph]].
	\bibitem{KF}K. Fukushima, D. E. Kharze	ev and H. J. Warringa, Phys. Rev. D \textbf{78}
	, 074033 (2008). [arXiv:0808.3382 [hep-ph]].
	\bibitem{DT}D. E. Kharzeev and D. T. Son, Phys. Rev. Lett. \textbf{106}, 062301 (2011) [arXiv:1010.0038 [hep-ph]].
	\bibitem{VP}V. P. Gusynin, V. A. Miransky and I. A. Shovkovy, Nucl. Phys. B \textbf{462}, 249 (1996) doi:10.1016/0550-3213(96)00021-1[hep-ph/9509320].

\end{thebibliography}

\end{document}


```