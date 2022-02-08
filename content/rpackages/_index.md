---
header:
  caption: ""
  image: ""
title: R packages
view: 4
---

I have written several R packages, some of which are published on CRAN and/or GitHub.

# `EloRating`

This is the first package I've ever written and it centers around Elo-rating as a means to analyse animal dominance interaction data. Since its beginning (as supplemental text files to [this paper](../publication/2011_neumann)) the package grew substantially and now allows a fairly refined characterization of dynamic and static dominance hierarchies, including manual setting of starting values, optimization routines, assessment of stability and more. 

Source code and installation instructions are here: [github](https://github.com/gobbios/EloRating).

[![CRAN_Status_Badge](https://www.r-pkg.org/badges/version/EloRating)](https://cran.r-project.org/package=EloRating)

# `EloChoice`

This package utilizes Elo-rating to assign scores to, and rank, stimuli that are presented to subjects as pairwise forced choices (see the accompanying paper with [Andrew Clark et al](../publication/2018_clark)). This package was my first excursion into C++, which made the calculation of Elo-ratings soo much faster.

Source code and installation instructions are here: [github](https://github.com/gobbios/EloChoice).

[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/EloChoice)](https://cran.r-project.org/package=EloChoice)

# `avutils`

This is a set of tools concentrated around working with audio recordings of child vocalizations. The major purpose is to serve as an R interface for the [DiViMe virtual machine](https://github.com/srvk/DiViMe). In addition, it allows some rudimentary audio and video manipulation (e.g. extracting audio from video files, splitting audio files) and also has some basic functions to read and write [ELAN files](https://tla.mpi.nl/tools/tla-tools/elan/).

Source code and installation instructions are here: [github](https://github.com/gobbios/avutils).

# `socialindices`

A collection of R functions to calculate sociality measures like CSI and association indices. This package has been largely dormant for a while, but I plan to get back to it as soon as I find the time.

Source code and installation instructions are here: [github](https://github.com/gobbios/socialindices).

# `cfp`

This is a collection of personal helper functions. I update this according to my personal needs.

Source code and installation instructions are here: [github](https://github.com/gobbios/cfp).

# `radagio`
 
This is an R wrapper for the ADAGIO ranking algorithm (see [here](http://ngonga.github.io/adagio/)). With this package ADAGIO becomes available from within R. I don't plan to update this package anymore as the original ADAGIO project seems to be inactive for some time.

Source code and installation instructions are here: [github](https://github.com/gobbios/radagio).