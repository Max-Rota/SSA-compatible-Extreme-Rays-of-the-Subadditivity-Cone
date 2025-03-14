# SSA-compatible Extreme Rays of the Subadditivity Cone #

The subadditivity cone (SAC) is the polyhedral cone in entropy space defined by all instances of the subadditivity (and Araki-Lieb) inequality
for a given number of parties ${\sf N}$, and it is an outer bound for the quantum entropy cone. 
Most of its extreme rays violate the strong subadditivity inequality and therefore cannot be achieved by quantum states. 
This repository collects all known extreme rays of the SAC that satisfy strong subadditivity.


## Description ##

By convention, the number of parties ${\sf N}$ does not account for a possible additional ancillary subsystem that might be introduced to purify a density matrix realizing an entropy vector. 
Each extreme ray is presented in the form of a generating entropy vector whose components are given in lexicographic order. 
The table below presents the number of "genuine" ${\sf N}$-party orbits of SSA-compatible extreme rays of the SAC for each value of ${\sf N}$ 
(i.e., lifts of extreme rays already found for a smaller number of parties are not included), and it summarizes 
what is currently known about their realizability in terms of holographic graph models, hypergraph models, stabilizer states, or arbitrary quantum states.
When the exact number is unknown, the most up to date range is provided.



## Summary ##

| ${\sf N}$   | new rays | graphical | hyper-graphical | stabilizer | quantum   | non-quantum |
| :-: | :------: | :-------: | :-------------: | :--------: | :-------: | :---------: |
| 3   | 1        | 1         | 1               | 1          | 1         | 0           |  
| 4   | 1        | 1         | 1               | 1          | 1         | 0           |
| 5   | 6        | 6         | 6               | 6          | 6         | 0           |
| 6   | 208      | [150,156] | [152,208]       | [152,208]  | [152,208] | [0,56]      |




## Attribution ##

If you find this data useful for your research, please consider citing the following papers.

 * Derivation of all extreme rays at ${\sf N}=6$ and construction of 150 graph models, [arXiv:2412.15364](https://arxiv.org/abs/2412.15364):
~~~bibtex
  @article{He:2024xzq,
    author = "He, Temple and Hubeny, Veronika E. and Rota, Massimiliano",
    title = "{Algorithmic construction of SSA-compatible extreme rays of the subadditivity cone and the ${\sf N}=6$ solution}",
    eprint = "2412.15364",
    archivePrefix = "arXiv",
    primaryClass = "quant-ph",
    reportNumber = "CALT-TH 2024-049",
    month = "12",
    year = "2024"
  }
~~~

* Construction of a hypergraph model for one of the ${\sf N}=6$ extreme rays, [arXiv:2312.04074](https://arxiv.org/abs/2312.04074):
~~~bibtex
@article{He:2023aif,
    author = "He, Temple and Hubeny, Veronika E. and Rota, Massimiliano",
    title = "{Inner bounding the quantum entropy cone with subadditivity and subsystem coarse grainings}",
    eprint = "2312.04074",
    archivePrefix = "arXiv",
    primaryClass = "quant-ph",
    reportNumber = "CALT-TH 2023-050",
    doi = "10.1103/PhysRevA.109.052407",
    journal = "Phys. Rev. A",
    volume = "109",
    number = "5",
    pages = "052407",
    year = "2024"
}
~~~

* Construction of a hypergraph model for one of the ${\sf N}=6$ extreme rays, [arXiv:2307.10137](https://arxiv.org/abs/2307.10137):
~~~bibtex
@article{He:2023cco,
    author = "He, Temple and Hubeny, Veronika E. and Rota, Massimiliano",
    title = "{Gap between holographic and quantum mechanical extreme rays of the subadditivity cone}",
    eprint = "2307.10137",
    archivePrefix = "arXiv",
    primaryClass = "hep-th",
    reportNumber = "CALT-TH 2023-027",
    doi = "10.1103/PhysRevD.109.L041901",
    journal = "Phys. Rev. D",
    volume = "109",
    number = "4",
    pages = "L041901",
    year = "2024"
}
~~~




## Acknowledgments ##

For the paper [arXiv:2412.15364], M.R. acknowledges support from UK Research and Innovation (UKRI) under the UK government’s Horizon Europe guarantee (EP/Y00468X/1).
