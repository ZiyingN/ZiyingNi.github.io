---
title: "A High-Performance SIKE Hardware Accelerator"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'In this work, we proposed a high-performance hardware architecture for the SIKE protocol. The architecture includes an improved multiplier based on the high-performance finite field multiplication (HFFM) algorithm which is 15%–20.7% faster than the previous multiplier based on the HFFM algorithm and a unified adder/subtractor with radix 3b . In addition, it also comprises an efficient scheduler strategy that decomposes all the functions of SIKE into finite field Fp and then effectively schedules through optimized multiplication chains for maximal performance. The proposed architecture is synthesized and implemented on Xilinx Virtex-7 FPGA for all the four variants of SIKE having security levels from 1 to 5 and achieved 2.6%–7.8% faster speeds as well as consumed less equivalent number of slices (ENS) than the state-of-the-art designs. In the comparison of area and time (AT), the proposed architecture is 14.2%–34.5% lower than the previous architecture.'
date: 2022-03-04
venue: 'TVLSI'
paperurl: 'https://ieeexplore.ieee.org/document/9728760'
citation: 'Z. Ni, D. -E. -S. Kundi, M. O&lsquo;Neill and W. Liu, &quot;A High-Performance SIKE Hardware Accelerator; in <i>IEEE Transactions on Very Large Scale Integration (VLSI) Systems</i>, vol. 30, no. 6, pp. 803-815, June 2022'
---
This work undertakes high-performance SIKE architecture by utilizing fast modular multiplier [24] being designed for the special structure of SIKE primes. In addition, the full design incorporates the modular adder/subtractor, SHAKE module, and scheduler. The proposed adder/subtractor for architecture is designed on the same concept of special structure of SIKE primes and have same critical path as that of the modular multiplier to maintain the constant-time operations. The SHAKE module is especially designed to maintain the performance of the SIKE protocol. Furthermore, an efficient scheduling methodology is devised in this work to effectively manages each function in SIKE by converting it to finite field Fp and then schedules to achieve maximal performance from the designed hardware. The implementation results show that all our proposed SIKE accelerators with prime: p434 , p503 , p610 , and p751 are faster than the up-to-date available SIKE designs while consuming less area resources.[Code](https://github.com/ZiyingN/SIKE_Verilog)

[Download paper here](http://academicpages.github.io/files/paper3.pdf)

Recommended citation: Z. Ni, D. -e. -S. Kundi, M. O’Neill and W. Liu, "A High-Performance SIKE Hardware Accelerator," in IEEE Transactions on Very Large Scale Integration (VLSI) Systems, vol. 30, no. 6, pp. 803-815, June 2022, doi: 10.1109/TVLSI.2022.3152011.
