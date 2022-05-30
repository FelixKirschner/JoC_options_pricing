# Here we present the result obtain by running the code for different inputs. 

Note: In all examples for the outer range we set *B = 400* and *M = 200 000*.


## Univariate example (Bertsimas Popescu)
First consider the data from Table 1 in the paper:

strikes = [95 100 110 115 120]

prices = [12.875 8.375 1.875 0.625 0.25]

weights = [1]

For *K = 105* we get an *upper bound* of 5.125 and a *lower bound* of 3.875.

## Explicit example with two assets

strikes = [100 110;
          102 107]

prices = [12 3;
          10 6]

weights = [1 / 2 1 / 2]

For *K = 105* we get an *upper bound* of 7.4 and a *lower bound* of 2.387.

## Varying strikes 

strikes = [90 95 100 110 120; 90 96 102 107 115]

prices = [20 15.5 12 5.5 1; 20.5 15 10 6 0.75]

weights = [1 / 2 1 / 2]

We present the results as follows *(K, lower bound, upper bound)*

(90,16.875,20.25)

(95,12.792,15.7)

(100,8.708,11.55)

(105,4.625,8.016)

(110,1.675,4.75)

(115,0.0,2)

