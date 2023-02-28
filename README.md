# Experiments with ChatGPT
## Hamiltonians from simplicial complexes associated to text. 
- [Quantum Spin Hamiltonians from Random Weighted Simplicial Complexes and NLP Tasks](https://github.com/Amelie-Schreiber/chatgpt/blob/main/hamiltonian_from_simplicial_complex.ipynb)

- [Hamiltonians from Text and Random Simplicial Complexes](https://github.com/Amelie-Schreiber/chatgpt/blob/main/hamiltonian%20from%20text%20and%20simplicial%20complexes.ipynb)

## Hybrid Qudit Surface Codes (Chimera Codes)

- [Qubit-Qutrit Entangling](https://github.com/Amelie-Schreiber/chatgpt/blob/main/qubit_qutrit_entangling.ipynb)

- [Qudit Gates](https://github.com/Amelie-Schreiber/chatgpt/blob/main/qudit_gates_chatgpt.ipynb)

- [Clock and Shift Operators](https://github.com/Amelie-Schreiber/chatgpt/blob/main/clock_shift_matrices%20(1).ipynb)

## Clique Complex of Knowledge Graphs


## Interaction Graphs

- [Interaction Graphs](https://github.com/Amelie-Schreiber/chatgpt/blob/main/interaction_graphs%20(2).ipynb) notebook shows how to transpile a quantum circuit from one gate set to a chosen basis gate set, then compute the interaction graph and weighted interaction graphs in order to analyze interaction topology. This can help in choosing a hardware backend that is best suited to run the circuit and can be used in the design of quantum ASICs. The notebook ends with a comment on how one should apply persistent homology to study the weighted interaction graph. Circuits which transpile to a circuit with weighted interaction graph such that interactions have low persistence may imply less topological constraints on the hardware backend. In particular, if there is weak entanglement between two qubits due to low two-qubit gate count between those two qubits, then this will show up in the persistent homology of the weighted interaction graph and will imply that direct connectivity of those qubits is less necessary than two qubit with a high amount of interaction. This is quantifiable in terms of persistence diagrams and Betti numbers. 
