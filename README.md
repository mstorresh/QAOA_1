# QAOA_1

A small exercise of QAOA 

For the Energy: 

$E(s_0, s_1, s_2) = - s_0 + \frac{1}{2} s_1 - \frac{1}{2} s_2 + \frac{1}{2} s_0 s_1 + \frac{1}{2} s_1 s_2$

Where the Cost Hamiltonian is written as 

$H_c = \frac{1}{2} z_0 z_1 + \frac{1}{2} z_1 z_2 - z_0 + \frac{1}{2} z_1 - \frac{1}{2} z_2$

The one in Qutip has more calculations, and the one for qiskit just has 1 minimum. But both cases are expected to work for any n. In these cases they work with p =1 and p =2.
