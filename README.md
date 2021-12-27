# paper-ring-loading
This is the term paper I wrote during my M.Sc. degree in mathematics.
In this work, I analyzed the approximation algorithm presented in the 1999 paper "The Ring Loading Problem" by Schrijver, Seymour and Winkler [1].

This repository contains the LaTeX code used for the paper, the presentation and the figures.

The following is the abstract

## Abstract
The ring loading problem arises during the planning of SONET rings. Given a cycle
graph of n > 1 nodes and a traffic demand for each pair of nodes, the problem is to
determine a routing in which each demand is routed either completely in the clockwise
or completely in the counterclockwise direction around the ring, while minimizing the
maximal load on any edge.
Since this problem is NP-complete, Schrijver, Seymour and Winkler presented an
approximation algorithm in their paper “The Ring Loading Problem”. This algorithm
computes approximations that exceed the optimal solution by at most 1.5*D, where D is
the maximal demand. In the process, an optimal solution to the relaxed ring loading
problem is determined, which allows demands to be routed both ways at the same
time.
In this work, Schrijver et al.’s algorithm is presented and its is correctness proven.


# References
[1] Alexander Schrijver, Paul Seymour and Peter Winkler. _The Ring Loading Problem_ . SIAM Review 41 (4), 1999.
