# monet

This repository contains the code used to do the analysis and 
generate the figures in [arXiv:2209.01989: Log-correlated color
in Monet's paintings](https://arxiv.org/abs/2209.01989).

Beware evaluating the entire notebook: producing the correlation
functions takes 60-90GB of RAM! Procomputed correlation functions
are provided in the file `hueCs.mx`.

The Gaussian free field data in this reposity was generated using
a generic Wolff algorithm library produced by the same author,
available [here](https://git.kent-dobias.com/research/wolff/code/c++/).
