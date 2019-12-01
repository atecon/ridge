Package for running Ridge-regression using gretl.

Authors: Sven Schreiber and Artur Tarassow

This does not involve any cross-validation for obtaining some optimal shrinkage hyper-parameter 'lambda'. However, stay tuned for another package doing cross-validation coming soon! ;-)

Point coefficients as well as associated standard errors are returned for pre-defined lambda values.

Various statistics-of-fit are computed:
1) R-square as computed in scikit-learn
2) R-square as the squared correlation between reaizations and fitted values
3) Adjusted version of (2)
4) AIC
5) BIC
6) Generalized Cross-Validation statistics
