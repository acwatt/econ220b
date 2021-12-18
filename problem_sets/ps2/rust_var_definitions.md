n = 90 mileage bins
x = n x 1 values that x can assume, x = (1,...,n)'

c = n x 1 values that cost can assume,
c = (c(1,theta1),..., c(n,theta))'

ev = n x 1 that EV can assume,
ev = (EV_theta(1),..., EV_theta(n))'

pk = n x 1 that P(0|x,theta) can assume
pk = (P(0|1,theta),..., P(0|n,theta))'

P = n x n markov transition matrix (2.13)
P = (Pr(

T = number of periods
M = number of buses

lnp = 2x1 transition probabilities of x_diff = 0, 1 respectively


~ = horizontal concatenation
| = vertical concatentaion
.* element-wise multiplication
sumc(x) = column vector: column sum for each column of x. 

y = submat(x, r, c)
x (NxK matrix) – data
r (LxM matrix) – row indices
c (PxQ matrix) – column indices
y ((L*M)x(P*Q) matrix) – submatrix of x, y may be larger than x.
If r=0 (c=0), then all rows (columns) of x will be used.

