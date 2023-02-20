\documentclass{article}
\usepackage{amsfonts}

\begin{document}

\section{Algebraische Strukturen}

\subsection*{Aufgabe T-AS01 [5]}

$(\mathbb{N}, :)$

\subsection*{Anzahl der Operatoren}

Ein innerer binärer Operator:

\subsection*{Gruppe}

Eine innere Verknüpfung.

$\triangleright$ Bedingung erfüllt.

\begin{itemize}
\item \textbf{Abgeschlossenheit:} $a, b \in \mathbb{N}$ und $a \ast b \in \mathbb{N}$.
\item $\triangleright$ Bedingung nicht erfüllt, da $a:b$ nicht für alle $a, b \in \mathbb{N}$ in $\mathbb{N}$ liegt.
\item \textbf{Assoziativität:} Für $a, b, c \in \mathbb{N}$ ist $(a \ast b) \ast c = a \ast (b \ast c)$.
\item $\triangleright$ nicht erfüllt, da das Assoziativgesetz nicht bei Division gilt (Beispiel: $(5/3)/2 \neq 5/(3/2)$).
\item \textbf{Neutrales Element:} Für $a, e \in \mathbb{N}$ gilt $a \ast e = e \ast a = a$.
\item $\triangleright$ nicht erfüllt, da es keine Elemente $a,e \in \mathbb{N}$ außer $a=e$ gibt, für die $a \ast b = b\ast a$ gilt, was Bestandteil der Definition des neutralen Elements ist.
\item \textbf{Inverses Element:} Zu jedem Gruppenelement $a \in \mathbb{N}$ existiert ein inverses Element $a^{-1} \in \mathbb{N}$ für das gilt $a \ast a^{-1} = a^{-1} \ast a = e$.
\item $\triangleright$ nicht erfüllt, da kein neutrales Element existiert.
\end{itemize}

$\blacktriangleright$ Fazit: Keine Gruppe.

\subsection*{Abelsche Gruppe}

Prüfung ob Eigenschaft abelscher Gruppe erfüllt ist, d.h. dass die Verknüpfung symmetrisch ist. Es muss für $a, b \in \mathbb{N}$ gelten, dass $a \ast b = b \ast a$.

$\triangleright$ nicht erfüllt, da die Division nicht kommutativ ist.

\subsection*{Halbgruppe}

Eine innere Verknüpfung.

$\triangleright$ Bedingung erfüllt.

\begin{itemize}
\item \textbf{Abgeschlossenheit:} $a, b \in \mathbb{N}$ und $a \ast b \in \mathbb{N}$.
\item $\triangleright$ Bedingung nicht erfüllt, da $a:b$ nicht für alle $a, b \in \mathbb{N}$ in $\mathbb{N}$ liegt.
