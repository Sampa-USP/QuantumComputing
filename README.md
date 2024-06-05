# Quantum Computing

This repository provides a comprehensive tutorial designed to initiate simulations of material interactions at the atomic level using quantum computers.

## Sumário

1. [Quantum Computing Theory](/01.%20Quantum%20Computing%20Theory)
    - [1.1 Single Qubit System](/01.%20Quantum%20Computing%20Theory/01.%20Single%20Qubit%20System)
    - [1.2 Two or more independent Qubit System](01.%20Quantum%20Computing%20Theory/02.%20Two%20or%20more%20independent%20Qubit%20System)
    - [1.3 Two or more correlated Qubit System](/01.%20Quantum%20Computing%20Theory/03.%20Two%20or%20more%20correlated%20Qubit%20System)
    - [1.4 Logic Operators](01.%20Quantum%20Computing%20Theory/04.%20Logic%20Operators)
    - [1.5 Expected Value](01.%20Quantum%20Computing%20Theory/05.%20System's%20Expected%20Value)

2. [NISC Hardware](02.%20NISC%20Hardware)
    - [2.1 Quantum Hardwares](02.%20NISC%20Hardware/01.%20Quantum%20Hardwares)
        - [2.1.1 Superconductor QPU](02.%20NISC%20Hardware/01.%20Quantum%20Hardwares/Superconducting%20QPU.ipynb)
        - [2.1.2 Photonic QPU](02.%20NISC%20Hardware/01.%20Quantum%20Hardwares/Photonic%20QPU.ipynb)
        - [2.1.3 Neutral-Atom Based QPU](01.%20Quantum%20Hardwares/Neutral-Atom%20Based%20QPU.ipynb)
        - [2.1.4 Ion-Trapped QPU](02.%20NISC%20Hardware/01.%20Quantum%20Hardwares/Ion-Trap%20QPU.ipynb)
    - [2.2 Quantum Noise](02.%20NISC%20Hardware/02.%20Quantum%20Noise)
        - [2.2.1 Depolarization Error](02.%20NISC%20Hardware/02.%20Quantum%20Noise/Depolarization%20Error.ipynb)
        - [2.2.2 Initialization Error](02.%20NISC%20Hardware/02.%20Quantum%20Noise/Initialization%20Error.ipynb)
        - [2.2.3 Phase Damping Error](02.%20NISC%20Hardware/02.%20Quantum%20Noise/Phase%20Damping%20Error.ipynb)
        - [2.2.4 Readout Error](02.%20NISC%20Hardware/02.%20Quantum%20Noise/Readout%20Error.ipynb)
        - [2.2.4 Thermal Relaxation Error](02.%20NISC%20Hardware/02.%20Quantum%20Noise/Thermal%20Relaxation%20Error.ipynb)
    - [2.3 Quantum Noise Mitigation](02.%20NISC%20Hardware/03.%20Quantum%20Noise%20Mitigation%20Technique)
        - [2.3.1 Clifford Regression](02.%20NISC%20Hardware/03.%20Quantum%20Noise%20Mitigation%20Technique/Clifford%20Regression)
        - [2.3.2 Richardson Extrapolation](02.%20NISC%20Hardware/03.%20Quantum%20Noise%20Mitigation%20Technique/Richardson%20Extrapolation)

3. [Ab-initio Calculation](03.%20Ab-Initio%20Calculation)
    - [3.1 Building System's Hamiltonian](03.%20Ab-Initio%20Calculation/01.%20Building%20Systems%20Hamiltonian
        - [3.1.1 Bohr-Oppenheimer Approximation] (03.%20Ab-Initio%20Calculation/01.%20Building%20Systems%20Hamiltonian/01.Bohr-Oppenheimer%20approximation.ipynb)
        - [3.1.2 Fock Space](03.%20Ab-Initio%20Calculation/01.%20Building%20Systems%20Hamiltonian/02.Fock%20space.ipynb)
        - [3.1.3 Fermionic Creation and Annihilation Operators](03.%20Ab-Initio%20Calculation/01.%20Building%20Systems%20Hamiltonian/03.Fermionic%20creation%20and%20annihilation%20operators.ipynb)
        - [3.1.4 Slater Type Orbitals](03.%20Ab-Initio%20Calculation/01.%20Building%20Systems%20Hamiltonian/04.Slater-type%20orbitals.ipynb)
    - [3.2 Mapping Hamiltonian to Quantum Circuit](03.%20Ab-Initio%20Calculation/02.%20Mapping%20Hamiltonian%20to%20Quantum%20Circuit)
        - [3.2.1 Jordan-Wigner Transformation](03.%20Ab-Initio%20Calculation/02.%20Mapping%20Hamiltonian%20to%20Quantum%20Circuit/Jordan–Wigner_transformation.ipynb)
        - [3.2.2 Parity Transformation](03.%20Ab-Initio%20Calculation/02.%20Mapping%20Hamiltonian%20to%20Quantum%20Circuit/Parity_transformation.ipynb)
        - [3.2.3 Bravyi-Kitaev Transformation](03.%20Ab-Initio%20Calculation/02.%20Mapping%20Hamiltonian%20to%20Quantum%20Circuit/Bravyi-Kitaev_transformation.ipynb)
        - [3.2.4 Bravyi-Kitaev Superfast Transformation](03.%20Ab-Initio%20Calculation/02.%20Mapping%20Hamiltonian%20to%20Quantum%20Circuit/Bravyi-Kitaev_superfast_transformation.ipynb)
    - [3.3 Optimizing System Energy](03.%20Ab-Initio%20Calculation/03.%20Optimizing%20system%20energy)
        - [3.3.1 Optimization Algorithm](03.%20Ab-Initio%20Calculation/03.%20Optimizing%20system%20energy/01.%20Optimization%20Algorithms)
            - [3.3.1.1 Gradient-Free Optimizers](03.%20Ab-Initio%20Calculation/03.%20Optimizing%20system%20energy/01.%20Optimization%20Algorithms/Gradient-Free%20Optimizers)
            - [3.3.1.2 Gradient-Descent Optimizers](03.%20Ab-Initio%20Calculation/03.%20Optimizing%20system%20energy/01.%20Optimization%20Algorithms/Gradient-Descent%20Optimizers)
        - [3.3.2 VQE](03.%20Ab-Initio%20Calculation/03.%20Optimizing%20system%20energy/02.%20Variational%20Quantum%20Eigensolver%20(VQE))
    - [3.4 Mitigating Noise](03.%20Ab-Initio%20Calculation/04.%20Mitigating%20noise)
    - [3.5 Comparing Results](03.%20Ab-Initio%20Calculation/05.%20Comparing%20results)
