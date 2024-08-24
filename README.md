# Four-Body Contributions to $\bar{B} \to X_{s}\gamma$ at $\mathcal{O}(\alpha_{s})$

## Matrix $G^{(1)}_{ij}$

This Repository contains the rules and expressions that are necessary to construct the remaining four body contributions to the matrix $G^{(1)}_{ij}$.
These are the ones that are not already contained in the result of https://arxiv.org/abs/1411.7677, i.e. the ones that require FiveBody Gluon Bremsstrahlung Diagrams for IR cancellations.

The file \texttt{CombineGij.nb} together with the folder \textrm{Rules} contain all the neccessary ingredients for constructing our results. 

The matrix is split up into two parts: insertion I and insertion II, which represent the different topologies when inserting the operators.
Insertion I is built from the diagrams where there are two different fermion lines and insertion II from those with only one.

The building blocks are given in differential form as DB[i] and in integrated form IB[i]. 
The notebook also contains a routine to evaluate the matrix elements for given values of $m_b$, $m_q$, $\mu$ and the energy cut-off $\delta$.

## Integral Results

We also give the integrals that we computed. The file \texttt{Integrals.nb} contains the necessary routines that collect them from the \textrm{Rules} folder.
We give the four-body integrals in the two bases that we used (F-base of master integrals from reduction and G- or UT-base.).
The five-body integrals are given in the F-base.

All integrals als also given diagramatically (in the F-base).
