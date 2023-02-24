---
title: "Efficient Pipelining Exploration for a High-performance CRYSTALS-Kyber Accelerator"
collection: Eprint
permalink: /publication/paper-5
excerpt: 'The design methodology revolves around aggressively enabling maximum inter-module and intra module architectural parallelisation. To facilitate maximum throughput, FIFO-based buffering is provided and balanced to act as inter/intra-module pipelining. Area-time efficiency is high by effective resource reuse in case of NTT/INTT. A single NTT/INTT is computed in 128 cycles, once the pipeline is full. The FPGA based implementation results show that compared to the state-of-the-art, the proposed architecture delivers 24-52% speedups at three different security levels on Artix-7 and Zynq UltraScale+ devices, 50-75% reduction in DSPs and no BRAM resources usage for comparable security levels. Consequently, the AT product efficiency is reported to be 48-54% higher in comparison with the state-of-the-art designs.'
date: 2022-10-16
venue: 'IACR Eprint'
paperurl: 'https://eprint.iacr.org/2022/1093'
citation: 'Z. Ni, A. Khalid, M. O&lsquo;Neill and W. Liu, &quot;Efficient Pipelining Exploration for a High-performance CRYSTALS-Kyber Accelerator,&quot; <i>Cryptology ePrint Archive</i>. Paper 2022/1093, 2022.'
---
This work presents an ultra high-performance FPGA based Kyber accelerator that undertakes an optimally designed pipelined architecture for parallel execution of various modules in the design. The accelerator uses a pipelined MDC-NTT to speed up operations but to keep the area efficiency high, resource reuse is orchestrated during NTT/INTT. Multiple FIFOs are used to buffer data for pipeline balancing. We performed a hardware implementation of the proposed architecture using two different devices, the Artix-7 and the Zynq-UltraScale+. The results show that the proposed Kyber accelerator on the Artix-7 is 1.44×, 1.36×, and 1.25× faster for security levels 1/3/5, respectively. In terms of equivalent slice count, the proposed architecture reduces AT (area and time product) 16.2-27.8\% for the three different security levels. In the Zynq-UltraScale+ device, the proposed architecture achieves a speedup of 1.26-1.51× compared to the state-of-the-art designs reported till date.
[Download paper here](https://eprint.iacr.org/2022/1093)

Recommended citation: Z. Ni, A. Khalid, M. O&lsquo;Neill and W. Liu, &quot;Efficient Pipelining Exploration for a High-performance CRYSTALS-Kyber Accelerator,&quot; <i>Cryptology ePrint Archive</i>. Paper 2022/1093, 2022.
