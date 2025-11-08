# Ground State Optimizer for Nuclear Hamiltonian up to 3-body Interaction by Quantum Computing
## Team "Quantum-4-body" Members
|Name|GitHub|Role|
|:-:|:-:|:-:|
|Ritsuki Ito|[@rit-3525](https://github.com/rit-3525)|Quantum Krulov Subspace|
|Rei Takezawa|[@onagonanja](https://github.com/onagonanja)|-|
|Zhihao Deng|[@Deng-Zhihao](https://github.com/Deng-Zhihao)|VQE code development|
|Hideyuki Nishida|[@hnishida](https://github.com/hnishida)|-|
|Yuto Morohoshi|-|Mentor|

## Target
Understanding the dynamics of nuclear is crucial for particle physics research. For simple nuclears, Hamiltonian including up to 2-body interactions is sufficient for simulating their dynamics. However, for larger nuclears, $\text{}^3H$ and $\text{}^4He$ for instance, including 2-body interactions only shows disperancy with experiment value. On the other hand, Hamiltonian including 3-body interactions agree with the experiment well. Classical computers usually struggle in simulation with 3-body Hamiltonian. Quantum computing can help in accelarating the calculation. In this research, we tried different quantum computing algorithms for simulating 3-body Hamiltonian.

## Method and Results
### 1. Quantum Phase Estimation
### 2. Variational Quantum Eigensolver
![](./VQE/fig_VQE.png/)
![](./VQE/fig_VQE2.png/)
### 3. Quantum Krylov Subspace
![](./QKS/QKS_converge.png/)

## Reference
\[1]  <br />Steven C. Pieper, R. B. Wiringa, "Quantum Monte Carlo Calculations of Light Nuclei", arXiv:nucl-th/0103005
\[2]  <br />J. Carlson et al., "Quantum Monte Carlo methods for nuclear physics", arXiv:1412.3081
