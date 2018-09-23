# Testing Go

## Testing Go with Project Euler.  
This is a repository to keep my code for solving project Euler challenges. You can see the fantastic website and challenges [here](https://projecteuler.net/ "Project Euler").

---

## Why is this here?  
1. I would like to learn Golang and solve these challenges.
2.
![Because sharing (after solving for yourself) is caring.](images/reason2.jpg)

**Solve the challenges youself first.** After you have solved a challenge then please feel free to comment on the revelant issue if you would like and make suggestions! There are forums on the website itself as well which is a good place for discussion though it seems mostly people just posting their code. This repository is more _Go_ specific. 

---

Library details.

numbertheory:

primeNumbersBelowCeiling:  
This program creates a slice of all the numbers from 2 to the max prime size 'ceiling'. It uses a Euclidean sieve/Sieve of Eratosthenes to then find all the primes in the slice.

primeNumbersContinuously:  
This uses again an Euclidean sieve/Sieve of Eratosthenes but in parts. The program takes one small slice, the size of which is defined by the user and finds all the primes in that slice before moving on to a new slice. For each new slice it must check all the new numbers against the current prime numbers before sieving.

primeFactorisation:  
This program provides a prime factorisation of a number given at runtime. It simply checks whether each prime number in order is a factor and if so, how many times, before moving on to the next prime.

lowestCommonMultiple:  
Returns the lowest common multiple of a group of numbers. lcm by raising each prime factor to the maximum number of times that prime factor appears in any of the numbers and then multiplying each of these results.

numberOfDivisors:  
Returns the number of divisors a number has using its prime factorisation.  
![Insert explantion here (You can't see the picture)](images/numberOfDivisors.png)
