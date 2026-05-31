---
id: cell-complexes
aliases: []
tags:
  - algebraic-topology
  - cell-complexes
  - ch0
  - hatcher
source: Hatcher pp. 5-8
---

# Cell Complexes

This is the way that Hatcher likes to approach topological constructions formally. This sets up the general framework for [[simplicial complexes]] that are used heavily in [[topological data analysis]].

An ideal prerequisite to reading this section is to have a good understanding of classification of surfaces, as well as the construction of the torus and the Klein bottle haha.

> [!definition] An $n$-cell is a space homeomorphic to the open unit ball in $\mathbb{R}^n$. A cell complex is a space $X$ together with a partition of $X$ into cells such that for each cell $e_\alpha$, there is a map $\phi_\alpha: D^n \to X$ such that $\phi_\alpha$ maps the interior of $D^n$ homeomorphically onto $e_\alpha$, and $\phi_\alpha(\partial D^n)$ is contained in the union of cells of dimension less than $n$.
