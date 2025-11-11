# Quantum Mechanics Glossary

A quick reference guide to essential quantum terminology. Terms are organized alphabetically with intuitive explanations.

---

## A

### Amplitude
A complex number that encodes both the magnitude and phase of a quantum state. The square of the amplitude's magnitude gives the probability.

### Ancilla Qubit
An auxiliary qubit used in quantum algorithms to help with computation, but not part of the final answer.

### Angular Momentum
A measure of rotational motion. In quantum mechanics, it's quantized - only certain values are allowed.

---

## B

### Basis States
A set of quantum states that can be combined to create any other state in the system. For a qubit, |0⟩ and |1⟩ are common basis states.

### Bell States
Four specific maximally entangled states of two qubits:
- |Φ⁺⟩ = (1/√2)(|00⟩ + |11⟩)
- |Φ⁻⟩ = (1/√2)(|00⟩ - |11⟩)
- |Ψ⁺⟩ = (1/√2)(|01⟩ + |10⟩)
- |Ψ⁻⟩ = (1/√2)(|01⟩ - |10⟩)

### Bell's Theorem
A fundamental result showing that quantum mechanics cannot be explained by local hidden variables. Proves that quantum entanglement is genuinely non-classical.

### Bloch Sphere
A geometric representation of a single qubit as a point on the surface of a sphere. Useful for visualizing quantum states and operations.

### Born Rule
The fundamental rule relating quantum states to measurement probabilities: P = |⟨outcome|state⟩|²

### Bra
In Dirac notation, ⟨ψ| represents the conjugate transpose of the ket |ψ⟩. Think of it as a "row vector."

---

## C

### Classical Bit
The basic unit of classical information: 0 or 1. Cannot be in superposition.

### Coherence
The ability of a quantum system to maintain superposition and phase relationships. Lost through interaction with environment (decoherence).

### Collapse (Wave Function Collapse)
The process by which a quantum superposition reduces to a single definite state upon measurement.

### Commutator
A mathematical operation [A,B] = AB - BA that measures whether two operators can be measured simultaneously. If [A,B] = 0, they commute and can be precisely measured together.

### Complementarity
The principle that quantum systems can exhibit wave-like or particle-like properties, but not both simultaneously in the same measurement.

### Complex Conjugate
For a complex number z = a + bi, the complex conjugate is z* = a - bi. Flips the sign of the imaginary part.

### Copenhagen Interpretation
One interpretation of quantum mechanics: the wavefunction is complete, measurement causes collapse, and probabilities are fundamental.

---

## D

### Decoherence
The loss of quantum coherence due to interaction with the environment. Causes quantum systems to behave classically.

### Degeneracy
When multiple different quantum states have the same energy (or other property). The states are called degenerate.

### Density Matrix
A mathematical object ρ that represents quantum states, including mixed states (statistical mixtures). More general than wavefunctions.

### Deutsch's Algorithm
The first quantum algorithm to show speedup over classical algorithms. Solves a specific problem with one query instead of two.

### Dirac Notation
The standard notation for quantum mechanics using bras ⟨ψ| and kets |ψ⟩, invented by Paul Dirac.

---

## E

### Eigenstate
A state that remains unchanged (except for scaling) when an operator is applied to it. Measurement eigenstates are the definite outcomes.

### Eigenvalue
The scaling factor associated with an eigenstate. In quantum mechanics, eigenvalues are the possible measurement results.

### Eigenvector
Another term for eigenstate when thinking in linear algebra terms.

### Energy Levels
The discrete, quantized energy values that a quantum system can have. Electrons in atoms occupy specific energy levels.

### Entanglement
A quantum correlation between systems where measuring one instantly affects the other, regardless of distance. Cannot be explained classically.

### EPR Paradox
A thought experiment by Einstein, Podolsky, and Rosen arguing that quantum mechanics is incomplete. Led to development of Bell's theorem.

### Evolution (Unitary Evolution)
How quantum states change over time according to Schrödinger's equation. Preserves probabilities and is reversible.

---

## F

### Fidelity
A measure of how close two quantum states are to each other. F = 1 means identical, F = 0 means orthogonal.

### Fock State
A quantum state with a definite number of particles (photons, atoms, etc.).

---

## G

### Gate (Quantum Gate)
An operation that transforms quantum states. The quantum analog of classical logic gates (AND, OR, NOT).

### Ground State
The lowest energy state of a quantum system.

### Grover's Algorithm
A quantum algorithm that searches an unsorted database of N items in √N time, compared to N/2 for classical search.

---

## H

### Hadamard Gate
A quantum gate that creates equal superposition:
- H|0⟩ = (1/√2)(|0⟩ + |1⟩)
- H|1⟩ = (1/√2)(|0⟩ - |1⟩)

### Hamiltonian
The operator corresponding to total energy of a system. Governs how quantum states evolve over time.

### Hermitian Operator
An operator equal to its conjugate transpose (A† = A). Represents observable quantities. Has real eigenvalues.

### Hidden Variables
Hypothetical additional information that would make quantum mechanics deterministic. Ruled out by Bell's theorem experiments.

### Hilbert Space
The mathematical vector space where quantum states live. Can be infinite-dimensional.

---

## I

### Identity Operator
The operator I that leaves states unchanged: I|ψ⟩ = |ψ⟩.

### Inner Product
The operation ⟨φ|ψ⟩ that measures overlap between states. Gives a complex number.

### Interference
The phenomenon where probability amplitudes add or subtract, creating enhancement (constructive) or cancellation (destructive).

---

## K

### Ket
In Dirac notation, |ψ⟩ represents a quantum state. Think of it as a "column vector."

---

## L

### Linear Operator
A mathematical operation that preserves vector addition and scalar multiplication. All quantum operations are linear.

### Locality
The principle that objects are only influenced by their immediate surroundings. Quantum entanglement appears to violate this.

---

## M

### Many-Worlds Interpretation
An interpretation where all possible measurement outcomes occur in separate "branches" of reality. No wavefunction collapse.

### Measurement
The process of extracting classical information from a quantum system. Fundamentally changes the state.

### Mixed State
A statistical mixture of pure states, representing incomplete knowledge. Described by a density matrix.

### Momentum
Mass times velocity (p = mv). In quantum mechanics, related to wavelength through de Broglie relation.

---

## N

### No-Cloning Theorem
The fundamental result that an unknown quantum state cannot be perfectly copied. Prevents quantum xerox machines.

### Normalization
Ensuring that total probability equals 1. For state |ψ⟩ = α|0⟩ + β|1⟩, requires |α|² + |β|² = 1.

---

## O

### Observable
A measurable physical quantity (position, momentum, energy, spin, etc.) represented by a Hermitian operator.

### Operator
A mathematical object that transforms quantum states. Can represent measurements, gates, or evolution.

### Orthogonal
Two states |φ⟩ and |ψ⟩ are orthogonal if ⟨φ|ψ⟩ = 0. They're distinguishable and can't interfere.

### Orthonormal Basis
A basis where all states are normalized and mutually orthogonal. Like perpendicular unit vectors.

---

## P

### Pauli Matrices
Three fundamental 2×2 matrices (X, Y, Z) representing spin measurements and basic quantum gates.

### Phase
The angle of a complex number in polar form. Two states can have same probabilities but different phases.

### Phase Kickback
When a controlled operation causes the control qubit to pick up a phase from the target qubit.

### Photon
A quantum particle of light. Has both wave and particle properties.

### Planck's Constant (h)
A fundamental constant (h ≈ 6.626 × 10⁻³⁴ J·s) that sets the scale for quantum effects. Often use ℏ = h/(2π).

### Position Operator
The operator corresponding to measuring position. Has continuous eigenvalues.

### Probability Amplitude
A complex number whose squared magnitude gives probability. Can interfere.

### Projection
Measurement as projecting the state onto an eigenstate.

### Pure State
A state described by a single wavefunction, not a statistical mixture. Maximum knowledge about the system.

---

## Q

### Quantization
The restriction of physical quantities to discrete values rather than continuous ranges.

### Quantum
The minimum discrete amount of any physical entity. The "quanta" in quantum mechanics.

### Quantum Circuit
A sequence of quantum gates applied to qubits, analogous to a classical logic circuit.

### Quantum Speedup
When a quantum algorithm solves a problem faster than the best-known classical algorithm.

### Quantum State
The complete description of a quantum system, represented by a wavefunction or density matrix.

### Qubit
The quantum analog of a classical bit. Can be in superposition of |0⟩ and |1⟩.

---

## R

### Reduced Planck Constant (ℏ)
Equal to h/(2π) ≈ 1.055 × 10⁻³⁴ J·s. Appears frequently in quantum mechanics equations.

---

## S

### Schrödinger Equation
The fundamental equation governing how quantum states evolve in time:
iℏ ∂|ψ⟩/∂t = H|ψ⟩

### Separable State
A multi-particle state that can be written as a product of individual states. Not entangled.

### Shor's Algorithm
A quantum algorithm that factors large numbers exponentially faster than known classical algorithms.

### Spin
An intrinsic form of angular momentum possessed by particles. For electrons: spin-½.

### Superposition
The quantum principle that a system can be in multiple states simultaneously until measured.

### Superposition Principle
If |ψ₁⟩ and |ψ₂⟩ are valid states, then α|ψ₁⟩ + β|ψ₂⟩ is also valid (for any complex α, β).

---

## T

### Tensor Product
The operation ⊗ that combines separate quantum systems. For two qubits: |ψ⟩ ⊗ |φ⟩.

### Tomography (Quantum State Tomography)
The process of determining an unknown quantum state through many measurements.

### Tunneling
The quantum phenomenon where particles can pass through energy barriers that would be impossible classically.

---

## U

### Uncertainty Principle
The fundamental limit on simultaneously knowing certain pairs of properties (like position and momentum):
Δx · Δp ≥ ℏ/2

### Unitary Operator
An operator U that preserves inner products and probabilities. Satisfies U†U = UU† = I. Represents reversible quantum evolution.

---

## V

### Vector Space
A mathematical structure where vectors can be added and multiplied by scalars. Quantum states live in vector spaces.

---

## W

### Wave Function (ψ)
The mathematical function describing a quantum state. Its squared magnitude gives probability density.

### Wave-Particle Duality
The principle that quantum objects exhibit both wave-like and particle-like properties.

### Wave Packet
A localized wave representing a particle with some uncertainty in position and momentum.

---

## Z

### Zero-Point Energy
The lowest possible energy that a quantum system can have. Never exactly zero due to uncertainty principle.

---

## Quick Symbol Reference

| Symbol | Meaning |
|--------|---------|
| |ψ⟩ | Ket: quantum state |
| ⟨ψ| | Bra: conjugate transpose of ket |
| ⟨φ\|ψ⟩ | Inner product / overlap |
| H | Hamiltonian (energy operator) |
| ℏ | Reduced Planck constant |
| i | Imaginary unit (√(-1)) |
| † | Conjugate transpose |
| ⊗ | Tensor product |
| ρ | Density matrix |
| Δ | Uncertainty / standard deviation |
| ∂ | Partial derivative |

---

## Common States

| Notation | Description |
|----------|-------------|
| \|0⟩ | Computational basis state (like classical 0) |
| \|1⟩ | Computational basis state (like classical 1) |
| \|+⟩ = (1/√2)(\|0⟩ + \|1⟩) | Plus state (superposition) |
| \|-⟩ = (1/√2)(\|0⟩ - \|1⟩) | Minus state (superposition) |
| \|↑⟩ | Spin up |
| \|↓⟩ | Spin down |

---

*Keep this glossary handy as you explore quantum concepts!*
