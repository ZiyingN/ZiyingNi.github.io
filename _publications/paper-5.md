---
title: "HPKA: A High-Performance CRYSTALS-Kyber Accelerator Exploring Efficient Pipelining"
collection: publications 
permalink: /publication/paper-5
excerpt: 'The design methodology revolves around aggressively enabling maximum inter-module and intra module architectural parallelisation. To facilitate maximum throughput, FIFO-based buffering is provided and balanced to act as inter/intra-module pipelining. Area-time efficiency is high by effective resource reuse in case of NTT/INTT. A single NTT/INTT is computed in 128 cycles, once the pipeline is full. The FPGA based implementation results show that compared to the state-of-the-art, the proposed architecture delivers 24-52% speedups at three different security levels on Artix-7 and Zynq UltraScale+ devices, 50-75% reduction in DSPs and no BRAM resources usage for comparable security levels. Consequently, the AT product efficiency is reported to be 48-54% higher in comparison with the state-of-the-art designs.'
date: 2023-07-15
venue: 'TC' 
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10193838'
citation: 'Z. Ni, A. Khalid, D. -e. -S. Kundi, M. O'Neill and W. Liu, "HPKA: A High-Performance CRYSTALS-Kyber Accelerator Exploring Efficient Pipelining," in IEEE Transactions on Computers, doi: 10.1109/TC.2023.3296899.'
---
CRYSTALS-Kyber (Kyber) was recently chosen as the first quantum resistant Key Encapsulation Mechanism (KEM) scheme for standardisation, after three rounds of the National Institute of Standards and Technology (NIST) initiated PQC competition which begin in 2016 and search of the best quantum resistant KEMs and digital signatures. Kyber is based on the Module-Learning with Errors (M-LWE) class of Lattice-based Cryptography, that is known to manifest efficiently on FPGAs. This work explores several architectural optimizations and proposes a high-performance and area-time (AT) product efficient hardware accelerator for Kyber. The proposed architectural optimizations include inter-module and intra-module pipelining, that are designed and balanced via FIFO based buffering to ensure maximum parallelisation. The implementation results show that compared to state-of-the-art designs, the proposed architecture delivers 25-51% speedups for Kyber’s three different security levels on Artix-7 and Zynq UltraScale+ devices, and a 50-75% reduction in DSPs at comparable security level. Consequently, the proposed design achieve higher AT product efficiencies of 19-33%.

[Download paper here](https://ieeexplore.ieee.org/abstract/document/10193838)

Recommended citation: Z. Ni, A. Khalid, D. -e. -S. Kundi, M. O'Neill and W. Liu, "HPKA: A High-Performance CRYSTALS-Kyber Accelerator Exploring Efficient Pipelining," in IEEE Transactions on Computers, doi: 10.1109/TC.2023.3296899.
