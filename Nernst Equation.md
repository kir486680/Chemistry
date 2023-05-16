
**Definition:**

The Nernst Equation is an equation in electrochemistry that relates the reduction potential of an electrochemical reaction (half-cell or full cell reaction) to the standard electrode potential, temperature, and activities (often approximated by concentrations) of the chemical species undergoing [[Reduction]] and [[Oxidation]]. The Nernst Equation is as follows:

E = E° - (RT/nF) * ln(Q)

Where:
- E is the cell potential (the voltage of the cell).
- E° is the standard cell potential.
- R is the ideal gas constant.
- T is the temperature in Kelvin.
- n is the number of moles of electrons exchanged in the reaction (the stoichiometric coefficient).
- F is Faraday's constant (the amount of electric charge in one mole of electrons).
- Q is the reaction quotient, a measure of the relative amounts of reactants and products present during a reaction at a particular time.

**Context:**

The Nernst Equation is extremely important in the field of electrochemistry. It gives us a way to calculate what the voltage will be under [[Non-Standard Conditions]]. It is used in studying cell potentials, solubility equilibria, acid-base equilibria, and even in physiology for understanding nerve and muscle cell signaling. 

**Intuition:**

At its core, the Nernst Equation is about equilibrium. Remember, a redox reaction wants to reach a state where the forward and reverse reactions are happening at the same rate. But the real world isn't "standard" - temperatures vary, concentrations vary. So, the Nernst equation helps us account for these variances. 

Think of it like adjusting a recipe. The recipe gives you the "standard" instructions. But if you're cooking at high altitude, you need to adjust your recipe. The Nernst Equation is like those adjustments, but for redox reactions.

**Example:**

Suppose we have a galvanic cell based on the following redox reaction:

Zn(s) + Cu^2+(aq) ↔ Zn^2+(aq) + Cu(s) 

The standard electrode potentials are as follows: E°(Zn^2+/Zn) = -0.76 V and E°(Cu^2+/Cu) = 0.34 V. 

The standard cell potential E° would be E°(Cu^2+/Cu) - E°(Zn^2+/Zn) = 0.34 V - (-0.76 V) = 1.1 V. 

Now, suppose we have [Zn^2+] = 0.1 M and [Cu^2+] = 0.01 M at 25°C (298 K). We can plug these into the Nernst Equation to find the cell potential under these conditions.

First, we calculate the reaction quotient Q: Q = [Zn^2+] / [Cu^2+] = 0.1 / 0.01 = 10.

Then we plug into the Nernst Equation. In this case, n = 2 (because the zinc loses two electrons), and ln(10) ≈ 2.302. So we have:

E = 1.1 V - ((8.314 J/(mol*K) * 298 K) / (2 * 96485 C/mol)) * 2.302 = 1.1 V - 0.0592 V = 1.04 V

So under these conditions, the cell potential is 1.04 V. 

This example should help illustrate the utility of the Nernst Equation in predicting cell potentials under non-standard conditions.