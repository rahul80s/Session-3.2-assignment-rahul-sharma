# Session-3.2-assignment-rahul-sharma
Acagild session 3.2 assignment

1. Define matrix mymat by replicating the sequence 1:5 for 4 times and transforming into a matrix, sum
over rows and columns.

Ans 1 ->

mymat <- matrix(rep(seq(5), 4), ncol = 5)

apply(mymat, 1, sum)

apply(mymat, 2, sum)
