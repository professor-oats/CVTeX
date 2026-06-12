\begin{tikzpicture}[scale=2]

% base silhouette
\fill[green!50!black]
(0,0) -- (2,0.8) -- (2,-0.8) -- cycle;

% facets
\fill[green!30!black]
(0,0) -- (2,0.8) -- (1.2,0.2) -- cycle;

\fill[green!60!black]
(0,0) -- (2,-0.8) -- (1.2,-0.2) -- cycle;

% ridge
\draw[green!80!black, line width=0.8pt]
(0,0) -- (2,0);

% eyes
\fill[red!70!black] (1.5,0.25) circle (0.06);
\fill[red!70!black] (1.5,-0.25) circle (0.06);

% subtle outline
\draw[green!90!black, line width=0.6pt]
(0,0) -- (2,0.8) -- (2,-0.8) -- cycle;

\end{tikzpicture}

- - -
\definecolor{deep}{HTML}{0B2E1A}
\definecolor{mid}{HTML}{165A34}
\definecolor{light}{HTML}{2F8F56}
\definecolor{highlight}{HTML}{6FD98A}
\definecolor{shadow}{HTML}{06140B}
\definecolor{eye}{HTML}{B11226}

\begin{tikzpicture}[scale=2]

% === CRANIAL DOME ===
\fill[light] (0,1.8)--(-0.4,1.4)--(0,1.2)--cycle;
\fill[mid] (0,1.8)--(0.4,1.4)--(0,1.2)--cycle;
\fill[mid] (-0.4,1.4)--(-0.9,1.1)--(0,1.2)--cycle;
\fill[mid] (0.4,1.4)--(0.9,1.1)--(0,1.2)--cycle;
\fill[deep] (-0.9,1.1)--(-1.2,0.6)--(0,1.2)--cycle;
\fill[deep] (0.9,1.1)--(1.2,0.6)--(0,1.2)--cycle;

% === EYES ===
\fill[eye] (-0.25,0.55)--(-0.1,0.65)--(0,0.55)--(-0.1,0.45)--cycle;
\fill[eye] (0.25,0.55)--(0.1,0.65)--(0,0.55)--(0.1,0.45)--cycle;

% === SNOUT ===
\fill[highlight] (0,1.0)--(0.15,0.4)--(0,-0.2)--(-0.15,0.4)--cycle;
\fill[mid] (-0.15,0.4)--(-0.6,0.2)--(-0.3,-0.3)--cycle;
\fill[mid] (0.15,0.4)--(0.6,0.2)--(0.3,-0.3)--cycle;
\fill[shadow] (0,-0.2)--(-0.2,-0.6)--(0.2,-0.6)--cycle;

% === CHEEKS ===
\fill[mid] (-0.6,0.2)--(-1.1,0.0)--(-0.7,-0.3)--(-0.3,0.1)--cycle;
\fill[deep] (-0.7,-0.3)--(-1.2,-0.6)--(-0.5,-0.8)--(-0.3,-0.3)--cycle;

\fill[mid] (0.6,0.2)--(1.1,0.0)--(0.7,-0.3)--(0.3,0.1)--cycle;
\fill[deep] (0.7,-0.3)--(1.2,-0.6)--(0.5,-0.8)--(0.3,-0.3)--cycle;

% === JAW ===
\fill[shadow] (-0.5,-0.7)--(-0.2,-1.2)--(0,-0.8)--cycle;
\fill[deep] (-0.8,-0.6)--(-0.5,-0.7)--(-0.2,-1.2)--cycle;

\fill[shadow] (0.5,-0.7)--(0.2,-1.2)--(0,-0.8)--cycle;
\fill[deep] (0.8,-0.6)--(0.5,-0.7)--(0.2,-1.2)--cycle;

\fill[shadow] (-0.3,-1.2)--(0.3,-1.2)--(0,-1.5)--cycle;

\end{tikzpicture}
