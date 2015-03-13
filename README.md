Build Status from Travis CI [![Build Status](https://travis-ci.org/pierrepo/PBxplore.svg?branch=master)](https://travis-ci.org/pierrepo/PBxplore)

---

**PBxplore** is a suite of tools dedicated to Protein Block analysis. Protein Blocks are structural prototypes defined by [de Brevern](http://www.dsimb.inserm.fr/~debrevern/index.php) *et al* [1]. The 3-dimensional local structure of a protein backbone can be modelized as an 1-dimensional sequence of PBs. In principle, any conformation of any amino acid could be represented by one of the sixteen available Protein Blocks (see Figure 1).

![PBs](doc/img/PBs.jpg "PBs")

**Figure 1.** Schematic representation of the sixteen protein blocks, labeled from *a* to *p* (Creative commons CC BY).

# Download

- [Get latest zip archive](https://github.com/pierrepo/PBxplore/archive/master.zip)
- Clone repository: `git clone git@github.com:pierrepo/PBxplore.git` or `git clone https://github.com/pierrepo/PBxplore.git`

# Requirements

PBxplore requires: 

* Python 2.7 or Python 3.x (>= 3.3)
* the [NumPy](http://numpy.scipy.org/ "NumPy") Python library, 
* the R software.

Optionally, PBxplore can use:

* the [MDAnalysis](https://code.google.com/p/mdanalysis/) Python library to read MD trajectories generated by Gromacs (.xtc files),
* [WebLogo 3](http://weblogo.threeplusone.com/) to create logo from PB sequences.

# Documentation

- [Installation](doc/installation.md)
- [Introduction to Protein Blocks](doc/intro.PBs.md)
- [Single structure analysis](doc/single.structure.analysis.md)
- [Multiple conformation analysis](doc/multiple.conformation.analysis.md)


# References
[1] A. G. de Brevern, C. Etchebest and S. Hazout. Bayesian probabilistic approach for predicting backbone structures in terms of protein blocks. *Proteins* **41**: 271-288 (2000).
