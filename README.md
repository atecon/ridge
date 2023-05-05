**This package got retired and archived on 2023-05-05**

You can still find the gfn-function package file here:
https://github.com/atecon/ridge/blob/master/src/ridge.gfn

**Please use the *regls* addon written by Allin Cottrell instead:**

https://sourceforge.net/projects/gretl/files/addons/doc/regls.pdf


# Introduction
Package for running Ridge-regression using gretl.

**Authors**: Sven Schreiber and Artur Tarassow

## Description

This does not involve any cross-validation for obtaining some optimal shrinkage hyper-parameter 'lambda'.

Point coefficients as well as associated standard errors are returned for pre-defined lambda values.

Various statistics-of-fit are computed:
1) R-square as computed in scikit-learn
2) R-square as the squared correlation between reaizations and fitted values
3) Adjusted version of (2)
4) AIC
5) BIC
6) Generalized Cross-Validation statistics
