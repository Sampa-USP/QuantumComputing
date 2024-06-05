Copy code
# QuantumComputing

Este repositório tem o roteiro de aprendizado de computação quântica aplicada ao cálculo de primeiros princípios.

## Sumário

1. [Quantum Computing Theory](#1-quantum-computing-theory)
    - [1.1 Single Qubit System](#11-single-qubit-system)
    - [1.2 Two or more independent Qubit System](#12-two-or-more-independent-qubit-system)
    - [1.3 Two or more correlated Qubit System](#13-two-or-more-correlated-qubit-system)
    - [1.4 Logic Operators](#14-logic-operators)
    - [1.5 Expected Value](#15-expected-value)

2. [NISC Hardware](#2-nisc-hardware)
    - [2.1 Tipos de Hardware Quântico](#21-tipos-de-hardware-quântico)
        - [2.1.1 Superconduction QPU](#211-superconduction-qpu)
        - [2.1.2 Photonic QPU](#212-photonic-qpu)
        - [2.1.3 Neutral-Atom Based QPU](#213-neutral-atom-based-qpu)
        - [2.1.4 Ion-Trapped QPU](#214-ion-trapped-qpu)
    - [2.2 Fontes de Ruído](#22-fontes-de-ruído)
    - [2.3 Técnicas de Redução de Ruído](#23-técnicas-de-redução-de-ruído)
        - [2.3.1 Clifford Regression](#231-clifford-regression)
        - [2.3.2 Richardson Extrapolation](#232-richardson-extrapolation)

3. [Ab-initio Calculation](#3-ab-initio-calculation)
    - [3.1 Building System's Hamiltonian](#31-building-systems-hamiltonian)
        - [3.1.1 Borh-Oppenheimer Approximation](#311-borh-oppenheimer-approximation)
        - [3.1.2 Fock Space](#312-fock-space)
        - [3.1.3 Fermionic Creation and Annihilation Operators](#313-fermionic-creation-and-annihilation-operators)
        - [3.1.4 Slater Type Orbitals](#314-slater-type-orbitals)
    - [3.2 Mapping Hamiltonian to Quantum Circuit](#32-mapping-hamiltonian-to-quantum-circuit)
        - [3.2.1 Jordan-Wigner Transformation](#321-jordan-wigner-transformation)
        - [3.2.2 Parity Transformation](#322-parity-transformation)
        - [3.2.3 Bravyi-Kitaev Transformation](#323-bravyi-kitaev-transformation)
        - [3.2.4 Bravyi-Kitaev Superfast Transformation](#324-bravyi-kitaev-superfast-transformation)
    - [3.3 Optimizing System Energy](#33-optimizing-system-energy)
        - [3.3.1 Optimization Algorithm](#331-optimization-algorithm)
            - [3.3.1.1 Gradient-Free Optimizers](#3311-gradient-free-optimizers)
            - [3.3.1.2 Gradient-Descent Optimizers](#3312-gradient-descent-optimizers)
        - [3.3.2 VQE](#332-vqe)
    - [3.4 Mitigating Noise](#34-mitigating-noise)
    - [3.5 Comparing Results](#35-comparing-results)
