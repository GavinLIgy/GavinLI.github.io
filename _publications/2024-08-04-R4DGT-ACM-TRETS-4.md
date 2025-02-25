---
title: "ProgramGalois: A Programmable Generator of Radix-4 Discrete Galois Transformation Architecture for Lattice-based Cryptography"
collection: publications
permalink: /publication/2024-08-04-R4DGT-ACM-TRETS-4
excerpt: 'This paper is about the design space exploration on radix-4 DGT framework.'
date: 2024-08-04
venue: 'ACM Trans. Reconfigurable Technol. Syst.'
paperurl: 'https://dl.acm.org/doi/10.1145/3689437'
citation: 'Guangyan Li, Zewen Ye, Donglong Chen, Wangchen Dai, Gaoyu Mao, Kejie Huang, and Ray C. C. Cheung. 2024. ProgramGalois: A Programmable Generator of Radix-4 Discrete Galois Transformation Architecture for Lattice-based Cryptography. ACM Trans. Reconfigurable Technol. Syst. Just Accepted (August 2024). https://doi.org/10.1145/3689437'
---

Lattice-based cryptography (LBC) has been established as a prominent research field, with particular attention on post-quantum cryptography (PQC) and fully homomorphic encryption (FHE). As the implementing bottleneck of PQC and FHE, number theoretic transform (NTT) has been extensively studied. However, current works struggled with scalability, hindering their adaptation to various parameters, such as bit-width and polynomial length. In this work, we proposed a novel DGT algorithm utilizing the radix-4 variant to achieve a higher level of parallelism to the existing NTT. Furthermore, to implement the efficient radix-4 DGT adapting more LBCs, we proposed a set of scalable building blocks, including a modified Barrett modular multiplier accepting arbitrary modulus utilizing only one integer multiplier, a radix-4 DGT butterfly unit, and a stream permutation network. The proposed modules are implemented on the Xilinx Virtex-7 and U250 FPGA to evaluate resource utilization and performance. Lastly, a design space exploration framework is proposed to generate optimized radix-4 DGT hardware constrained by polynomial and platform parameters. The sensitivity analysis showcases the generated hardware's performance and scalability. The implementation results on the Xilinx Virtex-7 and U250 FPGA show significant performance improvements over the state-of-the-art works, which reached at least 35%, 192%, and 68% ATP improvements in terms of LUTs, BRAMs, and DSPs, respectively.

[Check paper here](https://dl.acm.org/doi/10.1145/3689437)

Recommended citation: Guangyan Li, Zewen Ye, Donglong Chen, Wangchen Dai, Gaoyu Mao, Kejie Huang, and Ray C. C. Cheung. 2024. ProgramGalois: A Programmable Generator of Radix-4 Discrete Galois Transformation Architecture for Lattice-based Cryptography. ACM Trans. Reconfigurable Technol. Syst. Just Accepted (August 2024). https://doi.org/10.1145/3689437


