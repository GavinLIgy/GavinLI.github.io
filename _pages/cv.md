---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Eng in the Department of Electrical Engineering, City University of Hong Kong, 2020
* Ph.D in the Department of Electrical Engineering, City University of Hong Kong, 2025 (expected)

Internship Experiences
======
* Dec 2023 --- May 2024: Research Intern in Huawei HK
  * Research Intern - Huawei 2012 Laboratory, Theory Laboratory
  * Participated in a cluster system development project, responsible for optimizing the low-level program blocks.
  * Conducted several internal talks, technology sharings. And generated technical report. 

* July 2023 --- Oct 2023: Research Intern in Zhijiang Lab, Hangzhou, China
  * Research Intern - Zhijiang Lab
  * Participated in a NPU-based high-performance computing system development project, responsible for optimizing the low-level program blocks.
  * Conducted several internal talks, technology sharings. And generated technical report. 

Research Experiences
======
* June 2022 --- Sept 2023: Design Space Exploration Framework on Optimised Polynomial Multiplication Architecture on FPGA
  * Ph.D. Candidate - City University of Hong Kong, Hong Kong
  * Proposing a novel NTT variant utilizing the radix-4 method, to reduce the computing complexity compared to traditional NTT method.
  * Designing a highly efficient post-quantum crypto-system enhanced by the proposed split-radix NTT algorithm, showing significant performance improvements over the state-of-the-art designs on Xilinx Artix-7 FPGA.
  * Developing a deep understanding of hardware systems and cryptography, and technical writing skills to produce high-quality research publications. 
  * Supervisor: Prof. Ray Cheung

* July 2020 --- June 2022: Optimised Post-Quantum Cryptographic System on FPGA
  * Ph.D. Candidate - City University of Hong Kong, Hong Kong
  * Proposing a novel NTT variant utilizing the split-radix method, to reduce the computing complexity compared to traditional NTT method.
  * Designing a highly efficient post-quantum crypto-system enhanced by the proposed split-radix NTT algorithm, showing significant performance improvements over the state-of-the-art designs on Xilinx Artix-7 FPGA.
  * Developing a deep understanding of hardware systems and cryptography, and technical writing skills to produce high-quality research publications. 
  * Supervisor: Prof. Ray Cheung

* May 2020 --- Feb 2022: Secure RISC-V Platform for IoT Devices
  * Ph.D. Candidate - City University of Hong Kong, Hong Kong
  * Conducting literature reviews and experimental analyses to evaluate the feasibility of implementing post-quantum cryptography, AES, and ECDSA on constrained devices with limited power and memory resources.
  * Designing a hardware accelerator for the quantum-resistant cryptographic algorithm that can be extended to secure RISC-V IoT processors, leveraging knowledge of hardware design and cryptography.
  * Collaborating with PI and other researchers on the project to design and implement the hardware accelerator and evaluating its effectiveness in secure IoT platforms.
  * Supervisor: Prof. Ray Cheung

* May 2019 --- May 2020: Post-Quantum Cryptographic Hardware Design
  * Final Year Project - City University of Hong Kong, Hong Kong
  * Implemented a quantum-resistant cryptographic algorithm named as the Binary Ring LWE algorithm (BRLWE) in C, accelerated by an optimized NTT multiplication algorithm.
  * Conducted a hardware/software co-design, resulting in an SoC platform called Brlwesoc with UART port and the BRLWE C program running on.
  * Implemented the Brlwesoc on Lattice iCE40-HX8K FPGA board. Space, timing analysis and accuracy analysis are performed and the comparison on different parameter sets of the BRLWE is presented and discussed.
  * Supervisor: Prof. Ray Cheung

* May 2019 --- Aug 2019: Hardware Security
  * Research Assistant - LIRMM, Montpellier, France
  * Conducting a feasibility study on implementing the PicoRV32 processor on FPGA for a lightweight SoC platform.
  * Designing a hardware trojan in the PicoRV32 processor and attacked the AES program via simulation as part of the feasibility study on the lightweight SoC platform. 
  * Developing strong problem-solving skills, and experience with FPGA design and simulation tools.
  * Working effectively both independently and as part of a team in a fast-paced and dynamic research environment.
  * Supervisor: Dr. Sophie Dupuis
  
Selected Awards
======
* CityU EE Graduate Research Seminar Awards - First Prize - Semester A 2022/23
* 2023 IC Design Invitational Competition for College Students from Across-the-Taiwan-Straits, Hong Kong and Macau (2023年海峡两岸暨港澳大学生集成电路与电子设计邀请赛) - First Prize - Sept 2023
* Research Tuition Scholarship (RTS) - Full Tuition Fee - Academic Year 2023/24
* 2023 Guangdong Province Computer Society Outstanding paper award - 3rd Prize - - Jan 2024

Skills
======
* Coding Languages: Verilog HDL, VHDL, SpinalHDL, Scala, C/C++, Python, MATLAB.
* Linux x86 Development & Development: Perf, Intel VTune Profilier.
* Hardware Design Tools: Xilinx Vivado, Xilinx Vivado HLS, Verilator, VCS.
* Languages: Mandarin (native), English (proficient), Cantonese(basic).

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


Patents
======
* Cryptosystem With Utilizing Split-Radix Discrete Galois Transformation (inventor) - U.S. Patent Pending 18/337,391 - A method and system for key encapsulation processor with utilizing split-radix Discrete Galois Transformation for high performance.

* A Processor For A Cryptosystem (inventor) - U.S. Patent 12,093,198 B2 - A method and system for digital signature service including hardware accelerator modules and software processor.

<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
