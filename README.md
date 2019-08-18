# mersenne_numbers-lucas_lehmer-mersenne_primes
A simple program to calculate mersenne numbers, lucas lehmer series of the exponents of mersenne numbers and mersenne primes

A Mersenne number is any number that can be written as  2^p - 1  for some  p . For example, 3 is a Mersenne number (2^2 - 1) as is 31 (2^5 - 1).

We can test if a Mersenne number is prime using the Lucas-Lehmer test. Given a Mersenne number with exponent  p , the Lucas-Lehmer sequence can be defined as, 
no=4;
ni=(ni−12−2)mod(2p−1);


The Lucas-Lehmer accepts the exponent p  of a Mersenne number and returns the Lucas-Lehmer sequence up to  i=p−2 (inclusive)

For a given Mersenne number with exponent  p , the number is prime if the Lucas-Lehmer series is 0 at position  p−2. Mersenne Primes Gets a list of Prime numbers b/w given numbers a, b i.e. 3, 65 and tests whether the mersenne numbers b/w these are prime or not.
