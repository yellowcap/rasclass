rasclass
========
Supervised Raster Image Classification with R.

This package is [distributed through CRAN](https://cran.r-project.org/web/packages/rasclass/index.html).

Installation
------------
Rasclass can be installed within R with the standard package installer:

    install.packages('rasclass')

Description
-----------
This package contains functions to perform supervised and pixel based raster
image classification. It has been designed to facilitate land-cover analysis.
Five classification algorithms can be used: Maximum Likelihood Classification,
Multinomial Logistic Regression, Neural Networks, Random Forests and Support
Vector Machines. The output includes the classified raster and standard
classification accuracy assessment such as the accuracy matrix, the overall
accuracy and the kappa coefficient. An option for in-sample verification is
available.
