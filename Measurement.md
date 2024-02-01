## Measurement in the Z-Basis
- Although the laws of quantum mechanics permit this superposition of $|0\rangle$ and $|1\rangle$, it also demands that if we measure the qubit, such as at the end of a computation in order to read the result, we get a single, definite value.
- The probability is given by the norm-square of the amplitude. 
- Example: $\frac{2}{3}|0\rangle + \frac{1-2i}{3}|1\rangle$ 
	- Calculating the Norm Square: $$|\frac{2}{3}|^2 = \frac{4}{9}$$ and $$|\frac{1-2i}{3}|^2=\frac{1-2i}{3} \frac{1+2i}{3} = \frac{1+2i-2i-4i^2}{9}=\frac{5}{9}$$
- Measurement collapses the superposition^[[[Superposition]]]
- We say a quantum state is normalized if it's total probability is $1$, as it should be. Sometimes, we must find an overall normalization constant to make this true. For example, a qubit is in the state: $A(\sqrt{2}|0\rangle + |1\rangle)$. 
	- We find it by: ==COPY THESE NOTES LATER==
## Measurement in Other Bases
- Even though we introduced $|0\rangle$ and $|1\rangle$ as the north and south poles, respectively, of the Bloch Sphere. The Bloch Sphere is not a planet, and it is not spinning. 
- Any two opposite points could be taken as the north and south poles. For example, $|+\rangle$ and $|-\rangle$ could be the north and south poles, or $|i\rangle$ and $|-i\rangle$, or any opposite points. 
- A set of distinct measurement outcomes is called a basis, and {$|0\rangle$, $|1\rangle$} is called the **Z-Basis** because they lie on the z-axis of the Bloch Sphere ==Get the rest of the notes here==
- ==check notes for the rest of this section== 
## Bloch Sphere Mapping
### Global and Relative Phases
- We know that a qubit can be visualized as a point on the Bloch Sphere. Now, let us now learn how to determine where the point should be - how to map it on the Bloch Sphere.
- If the qubit from the prior example is multiplied by an overall, **global phase**, for some angle $\theta$: $$e^{i\theta}(\frac{\sqrt{3}}{2}|0\rangle+\frac{1}{2}|1\rangle)$$
- If we measure this in the Z-Basis, $\{|0\rangle, |1\rangle\}$ the probabilities of getting $|0\rangle$ and ==ADD NOTES==
- 