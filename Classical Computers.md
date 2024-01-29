## Universal Gates
- We do not need separate gates for all possibilities because we can reproduce al of them with just a few type of gates, called a universal set of gates
- We call a set of gates that can preform all possible logic operations a **universal gate set**
	- Two examples are {NOT, AND, OR} and {NAND}
- For classical computers, we could use 50% accurate gates. For quantum computers, we need 99.99% accuracy

## Adders
- To add two 4-bit numbers $A_3A_2A_1A_0$ and $B_3B_2B_1B_0$, we need to carry four numbers $C_{4}C_3C_2C_1$ and we get a five bit sum $S_{4}S_3S_2S_1S_0$
- The leftmost carry is the leftmost digit of the sum, $S_4=C_4$
- Half Adder- for the rightmost columns, which adds two bits and outputs a carry and a bit of the sum
- Full Adder- for the remaining column, which adds three bits and outputs a carry and a bit of the sum
- Ripple Carry Adder- by stringing together a half adder CHECK NOTES ONLINE

## Half Adder
- In general, there are four possibilities for adding two bits.
- CHECK NOTES ONLINE +  ADD SCREENSHOT OF SLIDES HERE  
## Full Adder
- Adds three bits, and outputs a carry and a bit of a sum. ADD SCREENSHOT OF SLIDES HERE
- A full adder takes to half adders and an OR gate

## Ripple Carry Adder
- Grab photo from this slide as well, for both the half adder and the full adder one

## Reversible Logic Gates
- a reversible gate is a logic gate where, given the outputs of the gate, we can always determine what the inputs were. 
	- An example is the not gate
- A non-reversible gate is CHECK NOTES
- If there are fewer input bits than output bits, the circuit is still irreversible because some of the outputs will still be undetermined
- Reversibility only applies to gates, not adders or any other combination of gates
### Toffoli Gate
- look at slides