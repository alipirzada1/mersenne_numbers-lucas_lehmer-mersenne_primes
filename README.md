# mersenne_numbers-lucas_lehmer-mersenne_primes
A simple program to calculate mersenne numbers, lucas lehmer series of the exponents of mersenne numbers and mersenne primes

A Mersenne number is any number that can be written as  2^p - 1  for some  p . For example, 3 is a Mersenne number (2^2 - 1) as is 31 (2^5 - 1).

We can test if a Mersenne number is prime using the Lucas-Lehmer test. Given a Mersenne number with exponent  p , the Lucas-Lehmer sequence can be defined as, 
                                             n0=4
                                    ni=(n2i−1−2)mod(2p−1) 

