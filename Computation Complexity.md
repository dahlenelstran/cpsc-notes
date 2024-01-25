## Asymptotic Notation
- If you want to add 2 4-bit numbers, you need the ripple-carry adder. If we generalize that, with the construction of the ripple carry adder, we have:
>To add two $n$-bit numbers, it takes one half-adder, $(n-1)$ full adders, for a total of $2+(n-1)5=5n-3$ logic gates. 
- Notation: we need $\exists$, $\ni$, $\forall$. ($\ni$ represents "such that")
- ==INSERT IMAGE FROM COMPUTATIONAL COMPLEXITY SLIDE==
## Complexity Classes
- Since each logic gate takes some time to apply, we say that an algorithm that utilizes, for example, O(n) logic gates, takes O(n) time, ignoring the fact that some gates can be run in parallel
- An algorithm is efficient if it takes polynomial time or less
- Any algorithm that is not efficient, taking more than polynomial time, is called superpolynomial
- We call problems easy if the solution is efficient, hard if the solution is inefficient
- Exponential functions $f_e(n)$ are faster than polynomial $f_p(n)$ until the intersection between the two functions. So when you pass $n$ such that $f_p(n) < f_e(n)$, this is where quantum computers have an advantage on hard problems. Therefore we should use classical computers for easier problems (small $n$), and quantum for harder problems (big $n$).
- Different problems are easier or harder than others, so we sort them using complexity classes. 
	- Problems that can be solved efficiently in polynomial time by a classical computer are in the complexity class $P$. This stands for *polynomial* time.
		- The computer is given a problem, and it solves it.
	- Another complexity class is the problems for which a solution can be quickly verified by a computer in polynomial time. This class is called $NP$. The $N$ stands for *non-deterministic Turing machine* and the $P$ stands for *polynomial* again.
		- For $NP$ problems, propose a solution and the computer will verify it. 
		- Many practical problems are $NP$.
	- Certain problems within $NP$ have a special property called completeness, and we call these problems $NP-COMPLETE$. If we can find an efficient solution to any $NP-COMPLETE$ problem, then we can use it to find an efficient solution to any $NP$ problem. That is, the overhead in applying the algorithm to other $NP$ problems is at most polynomial, so an efficient solution to one $NP-COMPLETE$ problem yields an efficient solution to all $NP$ problems.
		- Examples include solving $n \times n$ Sudoku problems, determining whether a set of items can fit into certain boxes (bin packing problem), traveling salesman problem
	- It is known that all problems in $P$ are contained in $NP$, since if one can efficiently solve a problem, one can also efficiently check proposed solutions by comparing them to the answer. It is unknown if $NP$ contains any problems that are not in $P$. 
	- Another complexity class is $PSPACE$, which contains all the problems that can be solved by a computer using a polynomial amount of memory, without any limits on time. 
		- Examples: winning a generalized level of Super Mario Bros
		- It is known that $NP$ is contained in $PSPACE$ because one has unlimited of time to check all possible answers. Although it seems like $PSPACE$ should be a larger class of problems than $NP$, this has not been proven
		- ==ADD GRAPH ON COMPLEXITY CLASSES==