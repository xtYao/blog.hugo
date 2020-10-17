---
author: "Xiaotong Yao"
date: 2018-03-13
linktitle: SvABA
title: SvABA -- genome-wide detection of structural variants and indels by local assembly
highlight: true
---

[Full text](https://doi.org/10.1101/gr.221028.117)

## **Abstract**
Structural variants (SVs), including small insertion and deletion variants (indels), are challenging to detect through standard alignment-based variant calling methods. Sequence assembly offers a powerful approach to identifying SVs, but is difficult to apply at scale genome-wide for SV detection due to its computational complexity and the difficulty of extracting SVs from assembly contigs. We describe SvABA, an efficient and accurate method for detecting SVs from short-read sequencing data using genome-wide local assembly with low memory and computing requirements. We evaluated SvABA's performance on the NA12878 human genome and in simulated and real cancer genomes. SvABA demonstrates superior sensitivity and specificity across a large spectrum of SVs and substantially improves detection performance for variants in the 20–300 bp range, compared with existing methods. SvABA also identifies complex somatic rearrangements with chains of short (<1000 bp) templated-sequence insertions copied from distant genomic regions. We applied SvABA to 344 cancer genomes from 11 cancer types and found that short templated-sequence insertions occur in ∼4% of all somatic rearrangements. Finally, we demonstrate that SvABA can identify sites of viral integration and cancer driver alterations containing medium-sized (50–300 bp) SVs.