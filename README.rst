UnionFind Implementation in Python
==================================

Union-find is a data structure that maintains disjoint set (called connected
components or components in short) membership, and makes it easier to merge
(union) two components, and to find if two elements are connected (i.e., belong
to the same component).

This implements the "weighted-quick-union-with-path-compression" union-find
algorithm.  Only works if elements are immutable objects.

Worst case for union and find :math:`(N + M \log^* N)`, with :math:`N` elements
and :math:`M` union/find operations. The function :math:`\log^*` is the number
of times needed to take :math:`\log` (base 2) of a number until reaching 1. In
practice, the amortized cost of each operation is nearly linear [1]_.

Contents
--------

* Module ``unionfind`` with the class ``UnionFind``

* An example notebook ``UnionFindExamples.ipynb``

* License: MIT.

Requirements
------------

* ``numpy``


.. [1] http://algs4.cs.princeton.edu/lectures/

