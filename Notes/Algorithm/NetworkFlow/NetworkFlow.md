# Network Flow

## Overview

### Definitions of Network Flow

* Network $N = \langle V, E, c, s, t\rangle$ (有向連通圖) $G=\langle V, E \rangle$
  * Vector
    * Source $s$
    * Sink $t$
  * Edge
* Capacity $c$: for edge $\langle i, j \rangle$ corresponding to a non-negative real number $c(i, j)$
* Flow $f$
* Flow of Network $v(f)$
  * Maximum Flow $\max v(f)$
    * Minimum Cut
    * Residual Graph
* Residual Capacity

We can use some trick to regularize some problem

* Multiple source or sink => use another vector as new source or sink connect to them
* Negative edge => introduce another vector to make sure two vector have only one edge between them

### Limitation of Network Flow

* Capacity Constraints (容量限制)
* Flow Conservation (流量守恆、平衡條件)
  * input = output
  * out from source = in to sink
* Skew Symmetry
  * Positive Flow

### Cut

Let $N=\langle V, E, c, s, t \rangle$

$A\subset V$ and $S\in A, t \in \bar{A}$

...

### Arcs of Network Flow

### Augmenting Path

## Resources

* [MIT OpenCourseWare - 13. Incremental Improvement: Max Flow, Min Cut](https://www.youtube.com/watch?v=VYZGlgzr_As)
