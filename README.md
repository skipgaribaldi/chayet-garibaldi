# 3875-magma: magma code to support a paper by Chayet & Garibaldi

The code in this repo is meant to be run in Magma.  For an example, see the file "example.magma".

The files you may want to call as a consumer of this repo are:
* main.magma: Given a Killing-Cartan type (a string KC) and a field F, construct an algebra A, which is the algebra constructed from a simple algebraic group of type key over the field F in the paper "A class of continuous non-associative algebras arising from algebraic groups including E<sub>8</sub>" at https://arxiv.org/abs/2005.07618
* nonassoc-identities.magma: can be used to look for linear dependencies among monomials of up to a chosen degree.
* osborn.magma: the procedure check_PIs tests for a variety of polynomial identities and asks whether they might hold for a given algebra A.
