Package for running Ridge-regression using gretl. This does not involve any cross-validation.

Point coefficients as well as associated standard errors are returned for pre-defined lambda values.

Various statistics-of-fit are computed:
1) R-square as computed in scikit-learn
2) R-square as the squared correlation between reaizations and fitted values
3) Adjusted version of (2)
4) AIC
5) BIC
6) Generalized Cross-Validation statistics
