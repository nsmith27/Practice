```math
\documentclass{article}

\title{\LARGE \textbf{Comprehensive Vector Analysis Study Guide}}
\author{}
\date{}

\begin{document}

\maketitle
\tableofcontents
\newpage

\section{Vector Basics}

\subsection{Definition and Notation}
\begin{itemize}
    \item A vector is a quantity with both magnitude and direction
    \item Notation: $\vec{v}$, $\mathbf{v}$, or bold $\mathbf{v}$
    \item Components in 3D: $\mathbf{v} = (v_x, v_y, v_z)$ or $\mathbf{v} = v_1\mathbf{i} + v_2\mathbf{j} + v_3\mathbf{k}$
\end{itemize}

\subsection{Vector Operations}
\begin{itemize}
    \item \textbf{Addition}: $\mathbf{a} + \mathbf{b} = (a_x+b_x, a_y+b_y, a_z+b_z)$
    \item \textbf{Scalar multiplication}: $c\mathbf{a} = (ca_x, ca_y, ca_z)$
    \item \textbf{Magnitude}: $|\mathbf{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}$
    \item \textbf{Unit vector}: $\hat{\mathbf{v}} = \frac{\mathbf{v}}{|\mathbf{v}|}$
\end{itemize}

\subsection{Dot Product}
\begin{itemize}
    \item Definition: $\mathbf{a} \cdot \mathbf{b} = |a||b|\cos\theta = a_xb_x + a_yb_y + a_zb_z$
    \item Properties:
    \begin{itemize}
        \item Commutative: $\mathbf{a} \cdot \mathbf{b} = \mathbf{b} \cdot \mathbf{a}$
        \item Distributive: $\mathbf{a} \cdot (\mathbf{b} + \mathbf{c}) = \mathbf{a} \cdot \mathbf{b} + \mathbf{a} \cdot \mathbf{c}$
        \item Scalar result
    \end{itemize}
    \item Applications:
    \begin{itemize}
        \item Finding angles between vectors: $\cos\theta = \frac{\mathbf{a} \cdot \mathbf{b}}{|\mathbf{a}||\mathbf{b}|}$
        \item Projection of one vector onto another: $\text{proj}_\mathbf{b}\mathbf{a} = \frac{\mathbf{a} \cdot \mathbf{b}}{|\mathbf{b}|^2}\mathbf{b}$
        \item Testing orthogonality: $\mathbf{a} \cdot \mathbf{b} = 0$ if vectors are perpendicular
    \end{itemize}
\end{itemize}

\subsection{Cross Product}
\begin{itemize}
    \item Definition: $\mathbf{a} \times \mathbf{b} = |a||b|\sin\theta\, \hat{\mathbf{n}}$
    \item Component form: $\mathbf{a} \times \mathbf{b} = (a_yb_z - a_zb_y, a_zb_x - a_xb_z, a_xb_y - a_yb_x)$
    \item Determinant form:
    \begin{equation}
        \mathbf{a} \times \mathbf{b} = 
        \begin{vmatrix} 
            \mathbf{i} & \mathbf{j} & \mathbf{k} \\
            a_x & a_y & a_z \\
            b_x & b_y & b_z
        \end{vmatrix}
    \end{equation}
    \item Properties:
    \begin{itemize}
        \item Anti-commutative: $\mathbf{a} \times \mathbf{b} = -(\mathbf{b} \times \mathbf{a})$
        \item Distributive: $\mathbf{a} \times (\mathbf{b} + \mathbf{c}) = \mathbf{a} \times \mathbf{b} + \mathbf{a} \times \mathbf{c}$
        \item Vector result perpendicular to both input vectors
    \end{itemize}
    \item Applications:
    \begin{itemize}
        \item Area of parallelogram: $A = |\mathbf{a} \times \mathbf{b}|$
        \item Testing collinearity: $\mathbf{a} \times \mathbf{b} = \mathbf{0}$ if vectors are parallel
        \item Finding perpendicular vector to a plane
    \end{itemize}
\end{itemize}

\subsection{Triple Products}
\begin{itemize}
    \item Scalar triple product: $\mathbf{a} \cdot (\mathbf{b} \times \mathbf{c}) = 
    \begin{vmatrix} 
        a_x & a_y & a_z \\ 
        b_x & b_y & b_z \\ 
        c_x & c_y & c_z 
    \end{vmatrix}$
    \begin{itemize}
        \item Geometric meaning: Volume of parallelepiped
    \end{itemize}
    \item Vector triple product: $\mathbf{a} \times (\mathbf{b} \times \mathbf{c}) = \mathbf{b}(\mathbf{a} \cdot \mathbf{c}) - \mathbf{c}(\mathbf{a} \cdot \mathbf{b})$
\end{itemize}



\end{document}
```