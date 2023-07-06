# Electrochemical Thermodynamics Lecture Notes

## Free Energy and Cell Potential (ΔG & E cell)
- ΔG and E cell are related and will be discussed in detail.
- Free energy is what determines if the reaction will go backwards or forward. Gibbs free energy can be used to calculate the maximum reversible work that may be performed by system at a constant temperature and pressure. 
- Gibbs energy is minimized when a system reaches chemical equilibrium at constant pressure and temperature. 

## Electrochemical Cells and Redox Reactions
- Electrochemical cells allow us to separate redox reactions into two parts, which can be carried out in different locations.
- This separation can lead to interesting physical phenomena and can make the system more complex to understand.

## Oxidation and Reduction in Redox Reactions
- In a redox reaction, one species is oxidized (loses electrons) and another is reduced (gains electrons).
- Example: Zinc is oxidized and copper is reduced in a redox reaction. The electrons lost by zinc are gained by copper.

## Electrochemical Cells and Electron Transfer
- In an electrochemical cell, oxidation and reduction reactions are separated spatially.
- Electrons and ions need to be transferred between the two regions for the reaction to occur.
- Electrons are transferred through a wire or other electrical conductor.
- Ions are transferred through a salt bridge.

## Cell Notation and Convention
- A shorthand notation is used to represent electrochemical cells.
- The species undergoing oxidation is written on the left and the species undergoing reduction is written on the right.
- A double line represents the physical separation between the two half cells.
- The sign of E cell tells us the direction of the reaction and which electrode is the anode and which is the cathode.

## Connection between ΔG and E cell
- The free energy change (ΔG) of a reaction is related to the cell potential (E cell) by the equation ΔG = -nFE cell, where n is the number of electrons transferred and F is the Faraday constant.
- The sign of ΔG tells us about the spontaneity of the reaction. If ΔG = 0, the system is at equilibrium.

## Reaction Quotient (Q)
- Q is a measure of the state of the reaction at a particular instance.
- It is written just like the equilibrium constant but with current concentrations instead of equilibrium concentrations.
- Q is dimensionless because it is a ratio of concentrations to standard state concentrations.

## Standard State and ΔG
- The standard state is usually chosen to be 1 molar for species in solution and 1 atmosphere for gases.
- The standard state is used to define ΔG°, the standard free energy change.
- ΔG° is the free energy change when all species are in their standard states.
- ΔG for a reaction at any other state can be calculated using the equation ΔG = ΔG° + RT ln Q, where R is the gas constant, T is the temperature, and Q is the reaction quotient.

## More on Nernst equation 
The Nernst equation is a mathematical relationship that relates the concentration (or activity) of reactants and products in an electrochemical cell to the cell potential. It is commonly used to calculate the cell potential of half-cell reactions.

In an electrochemical cell, there are two half-reactions occurring at the anode and cathode, respectively. Each half-reaction involves the transfer of electrons between species. The Nernst equation allows us to calculate the cell potential for a specific half-reaction.

However, when we write the Nernst equation for a "half" reaction, we are actually using a shorthand notation to represent the full reaction, including the reference electrode/reaction. This is done to simplify the representation of the overall electrochemical cell.

Let's take an example to illustrate this concept. Consider the reduction of copper(II) ions (Cu^2+) to copper metal (Cu) in an electrochemical cell. The half-reaction for this process can be written as:

Cu^2+(aq) + 2e^- -> Cu(s)

To calculate the cell potential using the Nernst equation, we need to consider the concentration of Cu^2+ ions and the activities of Cu^2+ ions and copper metal. However, when we write the Nernst equation for this half-reaction, we use a shorthand notation:

E = E° - (0.0592/n) * log([Cu^2+])

Here, E represents the cell potential, E° is the standard cell potential for the half-reaction, 0.0592 is the value of the natural logarithm base (ln) divided by the number of electrons transferred (n), and [Cu^2+] represents the concentration of Cu^2+ ions.

Now, if we were to represent the full reaction, including the reference electrode/reaction, it would look like this:

Cu^2+(aq) + 2e^- -> Cu(s) (cathode) Pt(s) + 2H^+(aq) -> H2(g) + 2e^- (anode)

The reference electrode/reaction, in this case, involves the reduction of hydrogen ions (H^+) to hydrogen gas (H2) on a platinum electrode. However, when we write the Nernst equation for the half-reaction involving Cu^2+ ions, we assume that the reference electrode/reaction is being carried out using a standard hydrogen electrode (SHE).

By using the shorthand notation for the half-reaction, we are essentially assuming that the reference electrode/reaction is at its standard state, and its potential is zero. This allows us to simplify the calculation of the cell potential by focusing on the half-reaction of interest.

In summary, when we write the Nernst equation for a "half" reaction, we are using a shorthand notation to represent the full reaction, including the reference electrode/reaction. This shorthand assumes that the reference electrode/reaction is at its standard state, simplifying the calculation of the cell potential for the half-reaction of interest.

  
If we consider the full reaction, including the reference electrode/reaction, the Nernst equation would be modified to include both half-reactions. Let's continue with the example of the reduction of copper(II) ions (Cu^2+) to copper metal (Cu) in an electrochemical cell.

The full reaction, including the reference electrode/reaction, would be:

Cu^2+(aq) + 2e^- -> Cu(s) (cathode) Pt(s) + 2H^+(aq) -> H2(g) + 2e^- (anode)

To calculate the cell potential using the Nernst equation for this full reaction, we would write:

E = E°cell - (0.0592/n) * log([Cu^2+]/P(H2))

Here, E represents the cell potential, E°cell is the standard cell potential for the full reaction, 0.0592 is the value of the natural logarithm base (ln) divided by the number of electrons transferred (n), [Cu^2+] represents the concentration of Cu^2+ ions, and P(H2) represents the partial pressure of hydrogen gas.

The E°cell for this reaction would be the difference between the standard reduction potential of the copper(II) ion (Cu^2+/Cu) half-reaction and the standard reduction potential of the hydrogen ion (H^+/H2) half-reaction.

As an example, let's assume that the standard reduction potential for the Cu^2+/Cu half-reaction is +0.34 V, and the standard reduction potential for the H^+/H2 half-reaction is 0.00 V. The number of electrons transferred (n) is 2.

If the concentration of Cu^2+ ions is 1.0 M, and the partial pressure of hydrogen gas is 1.0 atm, we can calculate the cell potential using the modified Nernst equation:

E = 0.34 V - (0.0592/2) * log(1.0 M/1.0 atm)

By evaluating the logarithm and performing the calculation, we can determine the cell potential for this full reaction.

## How does gibbs energy changes with amount of substance 
In thermodynamics, the chemical potential (μ) is a measure of the potential energy of a substance per unit amount. It helps us understand how the free energy (G) of a system changes with respect to changes in the amount of substance.

When we consider a pure substance, the change in free energy (ΔG) with respect to the number of moles (n) is linear. This is because in a pure substance, the only interaction that matters is between the molecules of the same substance. The chemical potential (μ) of a pure substance is given by the equation μ = G/n, where G is the free energy and n is the number of moles.

Intuitively, in a pure substance, adding or removing molecules affects the total potential energy of the system in a straightforward manner. If you have twice the number of moles, you have twice the total potential energy, and if you have half the number of moles, you have half the total potential energy.

Let's consider an example of a pure substance, such as oxygen gas (O2). If we have two moles of oxygen gas, the total potential energy is double compared to having only one mole. This can be explained by the fact that each molecule of oxygen gas interacts with other oxygen molecules in the same way, resulting in a linear relationship between the amount of substance and the change in free energy.

However, in mixtures or solutions, the situation is more complex. The chemical potential (μ) of a component in a mixture is not linearly related to the amount of that component. Instead, it is defined as the change in free energy of the mixture (ΔG_mix) with respect to the change in the amount of the component (Δm).

The reason for this non-linear relationship is the presence of interactions between different components in the mixture. In a mixture, the molecules of different components can interact with each other, leading to additional contributions to the total potential energy.

Let's take an example of a mixture of two substances, such as ethanol (C2H5OH) and water (H2O). If we add more ethanol to the mixture, the interactions between ethanol molecules and water molecules come into play, affecting the overall potential energy of the system. The change in free energy of the mixture with respect to the change in the amount of ethanol will not be a simple linear relationship because it depends on the interactions between ethanol and water molecules.

To determine the chemical potential of a component in a mixture, we calculate the derivative of the free energy of the mixture with respect to the amount of that component (μ = dG_mix/dm). This derivative takes into account the non-linear effects caused by interactions between different components.

In summary, the linear relationship between the change in free energy and the amount of moles (μ = G/n) holds true for pure substances because the interactions are only between molecules of the same substance. In mixtures or solutions, the chemical potential (μ) is not linearly related to the amount of the component due to the interactions between different components, and it is defined as the derivative of the free energy of the mixture with respect to the amount of that component (μ = dG_mix/dm).

## Chemical potential 
The chemical potential, denoted as μ^(α)_j, represents the potential energy of a species (j) in a particular phase (α), such as a metal, electrolyte, or ionomer. It is defined as the change in Gibbs free energy (G) per change in the amount (m_j) of the species.

Mathematically, we can express μ^(α)_j as:
$$ \mu^{(\alpha)}_j = \left(\frac{\partial G_{\text{mix}}}{\partial m_j}\right)_{T,P,N_{\text{other}}} $$

Here, G_mix is the Gibbs free energy of the mixture, and the subscript T, P, and N_other indicate that the partial derivative is taken with respect to temperature, pressure, and the amounts of other components held constant.

Furthermore, we can relate μ^(α)_j to the standard chemical potential (μ^o_j) using the equation:
$$ \mu^{(\alpha)}_j = \mu^o_j + RT \ln(a^{(\alpha)}_j) $$

In this equation, R represents the ideal gas constant, T is the temperature, a^(α)_j denotes the activity of the species j in phase α, and ln represents the natural logarithm.

Now, let's discuss how the chemical potential changes with concentration. As the concentration (or amount) of a species increases, its chemical potential typically increases. This can be understood by examining the equation μ^(α)_j = dG_mix/dm_j.

When we increase the concentration of a species j, it means that we are adding more moles of that species to the system. As a result, the change in Gibbs free energy (dG_mix) increases, leading to a higher chemical potential (μ^(α)_j) to compensate for the increased potential energy.

It is important to note that while the term "potential" is used in the name "chemical potential," its units are in joules (J) rather than volts (V). The reason for this is that the chemical potential measures the potential energy per unit amount of substance, which is expressed in joules. The concept of chemical potential is closely related to the idea of potential energy, but it should not be confused with electric potential or voltage, which are measured in volts.

# Chemical Reactions and Miu 
The formula you mentioned, ΔG_rxn(T, P, n_1, ..., n_N) = Σv_i*μ_i(T, P, n_1, ..., n_N), is the Gibbs free energy change (ΔG) of a chemical reaction. It relates the change in Gibbs free energy of a reaction to the chemical potentials (μ_i) of the reactants and products, taking into account their stoichiometric coefficients (v_i). This equation holds at a given temperature (T), pressure (P), and the amounts of each species (n_1, ..., n_N) involved in the reaction.

To illustrate this concept, let's consider the generic reaction: aA ⇌ bB, where A and B are reactants, and a and b are their respective stoichiometric coefficients.

The Gibbs free energy change for this reaction can be expressed as:
ΔG_rxn(T, P, n_A, n_B) = b*μ_B(T, P, n_A, n_B) - a*μ_A(T, P, n_A, n_B)

Here, μ_A and μ_B represent the chemical potentials of species A and B, respectively, and n_A and n_B denote the amounts of A and B in the reaction mixture.

Next, we can derive the equation ΔG = ΔG^0 + RTln(Q) from this formula, where ΔG^0 is the standard Gibbs free energy change of the reaction, R is the ideal gas constant, and Q is the reaction quotient.

The reaction quotient (Q) is defined as the ratio of the product of the concentrations (or activities) of the products raised to their stoichiometric coefficients to the product of the concentrations (or activities) of the reactants raised to their stoichiometric coefficients.

For the reaction aA ⇌ bB, the reaction quotient (Q) is given by:
Q = ([B]^b / [A]^a)

Using the relation between chemical potentials (μ) and concentrations (c), which can be written as μ = μ^0 + RTln(c), we can substitute the chemical potentials in the Gibbs free energy equation as follows:

ΔG_rxn(T, P, n_A, n_B) = b*(μ^0_B + RTln([B]/c^0)) - a*(μ^0_A + RTln([A]/c^0))
                        = (b*μ^0_B - a*μ^0_A) + RT(b*ln([B]/c^0) - a*ln([A]/c^0))
                        = ΔG^0 + RTln(([B]/c^0)^b / ([A]/c^0)^a)
                        = ΔG^0 + RTln(Q)

In this derivation, ΔG^0 represents the standard Gibbs free energy change of the reaction, and c^0 represents a reference concentration.

Thus, we have derived the relationship ΔG = ΔG^0 + RTln(Q) from the expression involving chemical potentials. This equation allows us to relate the Gibbs free energy change of a reaction to the standard Gibbs free energy change and the reaction quotient, providing insights into the spontaneity and direction of the reaction under non-standard conditions.

## Properties of the electrochemical potential 

When considering the chemical potential (μ), the determination of its value relies on the underlying quantum mechanics of the system, specifically through the Schrödinger equation. The Schrödinger equation accounts for both the kinetic energy and potential energy of the particles involved.

In the context of electrochemical systems, we need to account for the partitioning of the electrostatic effects, which arise from both the nuclear electrostatics at the atomic level and the macro-scale electric potential. To incorporate these effects, an additional term, known as μ̄ (mu-bar), is introduced to the chemical potential.

The electrochemical potential, represented by μ̄, includes the classical electrostatic energy contribution associated with a particular species. This contribution accounts for the interaction between charged particles and the electric potential present in the system. In other words, it takes into consideration the influence of the electric field on charged species.

The electrochemical potential, μ̄, can be expressed as the sum of the chemical potential (μ) and the classical electrostatic energy (φ):
μ̄ = μ + φ

The electrostatic energy term (φ) accounts for the interactions between charged particles and the electric potential in the system. It depends on the charge of the species and the electric potential at a given point.

For charged species, the electrochemical potential becomes crucial in determining their behavior. The electrochemical potential gradient drives the movement of charged species, influencing processes like ion transport and charge transfer in electrochemical systems.

To illustrate this concept, let's consider an example of a galvanic cell, such as a simple zinc-copper cell. In this cell, zinc (Zn) undergoes oxidation at the anode, producing Zn^2+ ions, while copper (Cu^2+) ions undergo reduction at the cathode, depositing copper metal.

The movement of Zn^2+ ions from the anode to the cathode is driven by the difference in electrochemical potentials between the anode and the cathode. The electrochemical potential difference results from the difference in chemical potentials and the associated electrostatic energy contributions.

The electrochemical potential plays a significant role in determining the driving forces in electrochemistry. It influences the movement of charged species, the direction of electron flow, and the overall cell potential. The electrochemical potential gradient acts as the driving force for various electrochemical processes, including redox reactions, ion transport, and electrolysis.

In summary, the electrochemical potential (μ̄) combines the chemical potential (μ) and the classical electrostatic energy (φ) to account for the influences of charged species and the electric potential in a system. It determines the driving forces in electrochemistry, driving the movement of charged species and influencing various electrochemical processes.


# Measuring Voltage

When measuring the voltage (or potential difference) between two points on a wire, if the wire and the resistor are made of the same material, the voltage measurement is effectively capturing the difference in electrochemical potential (Δμ̄) of the electrons between those two points.

The expression for Δμ̄_e (change in electrochemical potential of the electrons) can indeed be written as Δμ̄_alpha_e - Δμ̄_beta_e, where Δμ̄_alpha_e represents the electrochemical potential of electrons at point alpha, and Δμ̄_beta_e represents the electrochemical potential of electrons at point beta.

To simplify this expression, we can use the relationship between electrochemical potential and electric potential (Δμ̄ = -eΔφ), where e represents the charge of an electron and Δφ represents the electric potential difference.

Substituting this relationship, we have:
Δμ̄_e = -eΔφ

Here, Δμ̄_e represents the change in electrochemical potential of the electrons, which is equal to the negative product of the electron charge (e) and the change in electric potential (Δφ).

Now, let's consider the scenario where two pieces of gold and titanium (Ti) are in contact with each other. Gold and titanium have different electrochemical potentials. When they are in contact, an electrochemical potential difference arises between them due to the difference in their electron energies.

However, this electrochemical potential difference can be compensated by the flow of electrons from the metal with a higher electrochemical potential to the metal with a lower electrochemical potential. This electron flow continues until an equilibrium is reached, and the potential difference between the two metals becomes zero.

In other words, when the two metals are in contact, there is a redistribution of electrons that equalizes the electrochemical potential difference. As a result, no potential difference is observed on a voltmeter when measuring between the contact points of the two metals.

In summary, when measuring the voltage between two points on a wire made of the same material, the measurement captures the difference in electrochemical potential of the electrons. This difference can be related to the electric potential difference using the relationship Δμ̄_e = -eΔφ. In the case of two different metals in contact, electrons flow to equalize the electrochemical potential difference, resulting in zero voltage measurement on a voltmeter.