# Solution to RSA-Factoring-Challenge
- To calculate the factors of a number n I will use a naive brute-force method called trial division which attempts to divide n by all numbers up to and including n.
- If there is no remainder the number is a factor.
- No number more than n/2 except n itself can be a factor of n so as an optimization I will only run the trial division on numbers up to n/2, and then add n to the factor list. Additionaly, 1 is a factor of all integers so it will be added to the list at the start and we will commence trial division at 2.
