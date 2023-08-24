# maximum likelihood estimation

MLE, the estimator maximizes the log likelihood function.

In broad generalization, MLE makes stricter assumptions (the full density) and is thus typically less robust but more efficient if the assumptions are met.

In some cases the two coincide, OLS being one notable example where the analytic solution is identical and hence the estimator behaves in the same way.

In some sense, you can think of an MLE (in almost all cases) as an MoM estimator because the estimator sets the expected value of the gradient of the log likelihood function equal to zero. In that sense, there are cases where the density is incorrect but the MLE is still consistent because the first order conditions are still satisfied. Then MLE is referred to as "quasi-ML".
 
