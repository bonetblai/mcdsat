Tool for rewriting queries in terms of views. The problem of query rewriting is encoded as a propositional theory such that the model of the theory are in correspondence with the valid rewritings of the query. The encoding is sound and complete meaning that:

  * every model of the theory is a valid rewriting (soudness), and
  * every minimal valid rewriting of the query appears as a model of the theory (completeness).

Hence, all valid and minimal rewritings can be obtained by enumerating all models of the theory. The theory does not guarantee that every model is a minimal rewriting.

For more details, see

  * Y. Arvelo, B. Bonet and M-E. Vida. _Compilation of Query-Rewriting Problems into Tractable Fragments of Propositional Logic_. Proc. of 21st Conf. on Artificial Intelligence (AAAI). 2006. Pages 225-230. [(PDF)](http://ldc.usb.ve/~bonet/reports/AAAI06-query.pdf)


---


Notes:

  * For obtaining the code, go to [http:source/checkout Source].


---


