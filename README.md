# Discriminant Analysis

[![Documentation Status](https://readthedocs.org/projects/discriminantanalysis/badge/?version=latest)](http://discriminantanalysis.readthedocs.org/en/latest/?badge=latest)
[![Build Status](https://travis-ci.org/trthatcher/DiscriminantAnalysis.jl.svg?branch=master)](https://travis-ci.org/trthatcher/DiscriminantAnalysis.jl)
[![Coverage Status](https://coveralls.io/repos/trthatcher/DiscriminantAnalysis.jl/badge.svg?branch=master&service=github)](https://coveralls.io/github/trthatcher/DiscriminantAnalysis.jl?branch=master)

#### Summary

**DiscriminantAnalysis.jl** is a Julia package for multiple linear and quadratic 
regularized discriminant analysis (LDA & QDA respectively). LDA and QDA are
distribution-based classifiers with the underlying assumption that data follows
a multivariate normal distribution. LDA differs from QDA in the assumption about 
the class variability; LDA assumes that all classes share the same within-class 
covariance matrix whereas QDA relaxes that constraint and allows for distinct 
within-class covariance matrices. This results in LDA being a linear classifier
and QDA being a quadratic classifier.

#### Documentation

Full [documentation](http://discriminantanalysis.readthedocs.org/en/latest/) is
available on Read the Docs.

#### Visualization

When the data is modelled via linear discriminant analysis, the resulting
classification boundaries are hyperplanes (lines in two dimensions):

<p align="center"><img alt="Linear Discriminant Analysis" src="doc/visualization/lda.png"  /></p>

Using quadratic discriminant analysis, the resulting classification boundaries
are quadratics:

<p align="center"><img alt="Quadratic Discriminant Analysis" src="doc/visualization/qda.png"  /></p>


## Getting Started ([example.jl](example/example.jl))

WIP
