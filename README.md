# FinancialMath
blackscholes

1.   Binomial model for options
2.   Stochastic model for stock price
3.   Ito’s formula
4.   Derivation of Black Scholes equation
5.   Partial differential equations: the heat equation
6.   Rewriting the BS equation as the heat equation
7.   Value of European call and put options
8.   American options
9.   Free boundary problems
10.   Linear complementarity problem
11.   Numerical methods: introduction
12.   Forward and backward methods
13.   LU-method
14.   Iterative methods

Exercises lecture 131.
Suppose  that S satisfies  the  stochastic  differential  equation dS=μSdt+σSdX, whereX(t) is a Wiener process.  
Use Ito’s lemma to find the stochasticdifferential equation forf(S) =Sn.

2. Suppose that S1 and S2 follow stochastic differential equations dSi=μiSidt+σiSidXi, fori= 1,2.  
HereX1andX2are both Wiener processes, but they arecorrelated:E(dX1dX2)  =ρdt,  with−1≤ρ≤1.   
Derive  Ito’s  lemma  for  afunctionf(S1,S2,t).

3. Show by direct substitution thatV(S) =aS, witha∈Ris a solution to theBlack-Scholes equation.
Do the same forV(t) =aert.  
This should not come asa surprise:  what do these solutions represent?

4. a.IfV(S) is a function ofSonly, and satisfies the Black-Scholes equation,what form doesV(S) have?  Hint:  sinceVdoes not depend ont, it satisfies anordinary differential equation.
This is a differential equation of Euler type.
Forsuch equations, certain powers ofSare known to be solutions (you just have tofigure out which power to use).
Then linear combinations also are solutions.
b.Now  consider  separation  of  variables  for  the  Black-Scholes  equation:  trysolutions of the formV(S,t) =A(t)B(S).  What ordinary differential equationsdo the functionsAandBsatisfy?  Can you solve those?



The first homework:
- discrete time models
- stochastic models for the stock price
- Ito calculus
- European options.
