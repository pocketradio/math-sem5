![[Pasted image 20250805115928.png]]
![[Pasted image 20250805120031.png]]
## special cases
1. Unbounded solutiion
	- If all the entering column coefficients are <= 0, then the lpp  has an unbound solution
	- ![[Pasted image 20250807142547.png]]
	  ![[Pasted image 20250807142723.png]]


2. Multiple solution
	- if a non basic variable has a zero coefficient in z row at optimum level then there exists an alternate optimum solution of the LPP
	- ![[Pasted image 20250808104727.png]]
		  ![[Pasted image 20250808104808.png]]
3. Infeasible solution
4. Degeneracy solution
	- when there is a tie between variables for choosing leaving variables at least one basic variable will ke zero in the next iteration at the solution column And the new solution is said to be degeneracy.
	- ![[Pasted image 20250808104902.png]]
	  ![[Pasted image 20250808104954.png]]
	- arbitrary removal of caring variable may result in no. of iteration before the optimality is reached this difficulty is overcome by using the following technique
		1. When there is a tie for  leaving variables we divide the elements of first unit Vectors lying on the tied rows by the corresponding elements of the entering and get a new min ration
		2. If the tie is broken choose the variable corresponding to min new ratio
		3. If the tie is not broken then the same procedure is repeated to the successive unit vectors
		4. If the. Tie is not broken even after exhausting all unit vectors the same procedure is repeated - with the column rectors of the simplex table from left to right until tie is broken.
		   ![[Pasted image 20250812090210.png]]
		![[Pasted