- The **Church-Turing Thesis** says that everything that is computable can be computed with a Turing Machine, although it could take a long time
- The Strong Church-Turing Thesis says that any model of computation, be it the circuit model or something else, can be simulated by a *probabilistic Turing Machine* (a Turing machine where the state of the system can be set probabilistically, such as by the flip of a coin) with at most polynomial overhead.
	- Quantum Computers would not violate the regular Church-Turing Thesis. The hope, however, is that quantum computers can violate the Strong Church-Turing Thesis, that they will efficiently solve problems that are inefficient on classical computers. While there is no proof of this hope, there is strong evidence. 
- The complexity class of problems efficiently solved by a quantum computer is called $BQP$. It stands for Bounded-Error Quantum Polynomial-Time. 