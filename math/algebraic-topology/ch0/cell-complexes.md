---
id: cell-complexes
aliases: []
tags:
  - algebraic-topology
  - topology
  - hatcher
  - ch0
  - cell-complexes
source: Hatcher, Algebraic Topology, pp. 5-8
---

# Cell Complexes

This is the way that Hatcher likes to approach topological constructions formally. This sets up the general framework for [[simplical complexes]] that are used heavily in [[topogical data analysis]].

An ideal prerequisite to reading this section is to have a good understanding of classification of surfaces, as well as the construction of the torus and the Klein bottle haha.

> [!definition] An $n$-cell is a space homeomorphic to the open unit ball in $\mathbb{R}^n$. A cell complex is a space $X$ together with a partition of $X$ into cells such that for each cell $e_\alpha$, there is a map $\phi_\alpha: D^n \to X$ such that $\phi_\alpha$ maps the interior of $D^n$ homeomorphically onto $e_\alpha$, and $\phi_\alpha(\partial D^n)$ is contained in the union of cells of dimension less than $n$.

Now, let's go through the construction methodology for these complexes.

1. Start with $X^0$, which are the $0$-cells, which are just the vertices of the complex.
2. Recursively form $X^n$ from $X^{n-1}$ by attatching $n$-cells via the maps $\phi_\alpha: S^{n-1} \to X^{n-1}$, where $S^{n-1}$ is the boundary of the $n$-cell. This process is called "attaching" the $n$-cells to the $(n-1)$-skeleton.
3. Stop at finite $X = X^n$ or $X = \bigcup_{n=0}^\infty X^n$.

> [!example] The torus can be constructed as a cell complex with one $0$-cell, two $1$-cells, and one $2$-cell. The $0$-cell is the point where the two $1$-cells meet, and the $2$-cell is attached to the $1$-cells in a way that creates the torus shape.

> [!example] The Klein bottle can be constructed as a cell complex with one $0$-cell, two $1$-cells, and one $2$-cell. The attachment of the $2$-cell is done in a way that creates the non-orientable surface of the Klein bottle.
