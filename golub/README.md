# Credit

This file is a merged version of the files found [here](https://github.com/ramhiser/datamicroarray/wiki/Golub-(1999)).

# Description

The Golub et al. (1999) data consist of 47 patients with acute lymphoblastic leukemia (ALL) and 25 patients with acute myeloid leukemia (AML). Each of the 72 patients had bone marrow samples obtained at the time of diagnosis. Furthermore, the observations have been assayed with Affymetrix Hgu6800 chips, resulting in 7129 gene expressions (Affymetrix probes).

As discussed in the Bioconductor manual, "ALL arises from two different types of lymphocytes (T-cell and B-cell)", so we may wish to consider the data in terms of three classes: AML, ALL-T, and ALL-B. We provide the option to consider the data as two or three classes. Also, the Golub data set is often seen in two forms. In one case, the data are partitioned into a training and a test data set: we provide these as `golub_train` and `golub_test`, respectively. In the other case, the training and the test data sets are combined into one data set: we have named this `golub`.

The Golub data set is possibly the most widely studied and cited microarray data set.

| Sample Size | Number of Features | Number of Classes | Disease |
|:-----------:|:------------------:|:-----------------:|:-------:|
| 72 | 7129 | 2 or 3 | Leukemia |

# Data Source and Preprocessing

We have collected the training, test, and combined versions of the Golub data from the [golubEsets package on Bioconductor](http://www.bioconductor.org/packages/release/data/experiment/html/golubEsets.html). According to the Bioconductor reference manual, the data have been "transformed slightly."

# Reference

[Link to Original Paper](http://www.sciencemag.org/content/286/5439/531.abstract)

## BibTeX Record

```
@article{Golub:1999un,
author = {Golub, T R and Slonim, D K and Tamayo, P and Huard, C and Gaasenbeek, M and Mesirov, J P and Coller, H and Loh, M L and Downing, J R and Caligiuri, M A and Bloomfield, C D and Lander, E S},
title = {{Molecular classification of cancer: class discovery and class prediction by gene expression monitoring.}},
journal = {Science},
year = {1999},
volume = {286},
number = {5439},
pages = {531--537},
month = oct
}
```

# Miscellaneous

[Project Website with Additional Materials](http://www.broadinstitute.org/cgi-bin/cancer/publications/pub_paper.cgi?mode=view&paper_id=43)


