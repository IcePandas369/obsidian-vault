---
id: deformation-retract
aliases: []
tags:
  - algebraic-topology
  - deformation-retract
  - ch0
  - hatcher
source: Hatcher pp. 2-5
---

# Deformation Retract

## Retraction

**Def** A **deformation retraction** of a space $X$ onto a subspace $A$ is a family of maps $f_t : X \to X$ for $t \in I$ such that $f_0 = 1_X$, $f_1(X) \subset A$, and $f_t|_A = 1_A$ for all $t$. The family $f_t$ is continuous in $t$ and $x$.A deformation retraction is a homotopy from the identity map on $X$ to a retraction of $X$ onto $A$.

**Def** For a map $f \colon X \to Y$, a **mapping cylinder** of $f$ is the quotient space $M_f = (X \times I) \sqcup Y / \sim$, where $\sim$ identifies $(x, 1)$ with $f(x)$ for all $x \in X$.
