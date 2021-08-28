# LucasLehmerPrimalityTest
-Calculates whether a given Mersenne number is prime or not. 


-The Lucas–Lehmer test works as follows. Let Mp = 2p − 1 be the Mersenne number to test with p an odd prime. The primality of p can be efficiently checked with a simple algorithm like trial division since p is exponentially smaller than Mp. Define a sequence by s_i = 4 if i = o, and s_i = s_(i-1)^2-2 otherwise. Then, Mp is prime if and only if s_(i-2) is congruent to 0 (mod Mp).


-Unfortunately I had to import a module as python has a relatively low depth of recursion, still the maximum i could get was p = 2329. 


-On Jan 10th 1876, Édouard Lucas verified by hand that 2^127-1 is prime!
