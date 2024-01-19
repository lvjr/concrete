# The `concrete` bundle: A collection of flat beamer themes for LaTeX presentations

```
Author:  Jianrui Lyu <tolvjr@163.com>
Website: https://github.com/lvjr/concrete
License: The LaTeX Project Public License 1.3c
```

## 1\. Introduction

The `concrete` bundle provides a collection of flat beamer themes for making LaTeX presentations, especially for academic and scientific presentations.

It consists of the following seven beamer themes:

- light background themes
  - beamer theme bernoulli
  - beamer theme fermat
  - beamer theme lagrange
  - beamer theme riemann
- dark background themes
  - beamer theme dirichlet
  - beamer theme gauss
  - beamer theme mobius

## 2\. Usage

After installing this bundle, you can write a document like this:

```
\documentclass[xcolor={rgb}]{beamer}
\usetheme{bernoulli}
\begin{document}

\title{Beamer Theme Bernoulli}
\subtitle{A nice theme for LaTeX presentations}
\author{Author Name}
\institute{Institute Name}

\begin{frame}[plain]
\titlepage
\end{frame}

\section{Section One}

\subsection{Subsection One}

\begin{frame}{Frame Title}
Frame \insertframenumber
\end{frame}

\begin{frame}{Frame Title}
Frame \insertframenumber
\end{frame}

\subsection{Subsection Two}

\begin{frame}{Frame Title}
Frame \insertframenumber
\end{frame}

\begin{frame}{Frame Title}
Frame \insertframenumber
\end{frame}

\section{Section Two}

\subsection{Subsection One}

\begin{frame}{Frame Title}
Frame \insertframenumber
\end{frame}

\begin{frame}{Frame Title}
Frame \insertframenumber
\end{frame}

\subsection{Subsection Two}

\begin{frame}{Frame Title}
Frame \insertframenumber
\end{frame}

\begin{frame}{Frame Title}
Frame \insertframenumber
\end{frame}

\end{document}
```

Note that you **NEED** to add `xcolor={rgb}` option in loading `beamer` class. You can also have a look at the demo files included in this bundle.
