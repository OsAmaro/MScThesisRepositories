# MScThesis

Link to thesis pdf: https://fenix.tecnico.ulisboa.pt/cursos/meft/dissertacao/1128253548922708

Links to the repositories referred to in the MSc Thesis

https://github.com/RePlasma/PhysRevA.103.062608 \
"Simulating non-native cubic interactions on noisy quantum machines" \
Original authors: Yuan Shi et al \
In these notebooks we run direct Hamiltonian simulation on IBMQ machines and (ideal) variational quantum simulation VQS on the PennyLane API. \
paper: https://journals.aps.org/pra/abstract/10.1103/PhysRevA.103.062608 \
preprint: https://arxiv.org/abs/2004.06885

https://github.com/RePlasma/HamiltonianSimulation \
"Hamiltonian Simulation" \
Simulation of simple Hamiltonian as in Nielsen & Chuang \
Original authors: Michael A. Nielsen, Isaac L. Chuang \
Proof that the algorithm for simulating a Hamiltonian of the type $\otimes Z$ for a time $\Delta t$ works. The pdf is a print of the Mathematica notebook implementing this setup.

https://github.com/RePlasma/arXiv0709.1704 \
"Quantum simulation of the single-particle Schrodinger equation" \
Original authors: Giuliano Benenti, Giuliano Strini \
In this paper by Giuliano Benenti and Giuliano Strini the authors describe how to build quantum circuits to implement the unitary operator $U=e^{-i \Delta t H}$ for different external potentials and initial conditions. The pdf is a print of the Mathematica notebook implementing some of these setups.

https://github.com/RePlasma/New_J._Phys._20_113022 \
"Learning the quantum algorithm for state overlap" (Improved algorithms for the SWAP test through Machine Learning) \
Original authors: Lukasz Cincio, Yiğit Subaşı, Andrew T Sornborger and Patrick J Coles \
url: https://iopscience.iop.org/article/10.1088/1367-2630/aae94a \
In this notebook we reproduce Figure 9 for IBM computer ibmq_manila. See the pdf for a print of the notebook. \
"Abstract Short-depth algorithms are crucial for reducing computational error on near-term quantum computers, for which decoherence and gate infidelity remain important issues. Here we present a machine-learning approach for discovering such algorithms."..."Here, we find algorithms that have shorter depths than the Swap Test, including one that has a constant depth (independent of problem size)." ..."demonstrate that the shorter algorithms that we derive significantly reduce the error—compared to the Swap Test—on these computers."

https://github.com/RePlasma/PhysRevA.100.062315 \
"Quantum algorithm for the Vlasov equation" \
Original authors: Alexander Engel, Graeme Smith, and Scott E. Parker \
url: https://journals.aps.org/pra/abstract/10.1103/PhysRevA.100.062315 \
preprint: https://arxiv.org/abs/1907.09418 \
In this Mathematica notebook we (classically) simulate the evolution of the distribution+electric field of a linear and electrostatic plasma. The electric field will experience Landau damping. See pdf for a print of the notebook. \
Abstract: "...By linearizing and assuming a Maxwellian background distribution function, we convert the Vlasov-Maxwell system into a Hamiltonian simulation problem..."

https://github.com/RePlasma/10.1017-S002237782000118X \
"Carleman linearization of the Kompaneets equation" \
Following the papers [1] and [2], we modify the code of the former to solve the Kompaneets equation through Carleman linearization, and reproduce figure 4 of the latter using the pdepe function in Matlab. \
[1] Efficient quantum algorithm for dissipative nonlinear differential equations https://arxiv.org/abs/2011.03185, with code in https://github.com/hermankolden/CarlemanBurgers \
[2] Compton scattering in particle-in-cell codes https://www.cambridge.org/core/journals/journal-of-plasma-physics/article/abs/compton-scattering-in-particleincell-codes/4A2BE5F3AB821F6B7D45E36CC0FBB48F
