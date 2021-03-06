
## Benchmarking [IntaRNA](https://github.com/BackofenLab/IntaRNA)'s extension for structure probing (SHAPE) data

This repository contains data and analysis scripts for [IntaRNA](https://github.com/BackofenLab/IntaRNA)'s extension for structure probing (SHAPE) data and the respective publication.

In the following, we provide IntaRNA interaction heatmap representations as well as interaction site probabilities for target pre-mRNAs of the splicosomal U1 RNA.
A description how the U1 data extraction procedure is given [here](./data/U1/data-extraction.md).

Below figures compare the influence of *in vivo* SHAPE data on the predicted accessibility (unpaired probability) of the U1 RNA. The probablitiy corresponds to the 3-mer accssibilities (*RNAplfold -u 3*), such that for each position *i* the probability that 3-mer [*i-2, i*] is unpaired. 

![U1 accessibility](./data/U1/figures-U1-secondary-structure.svg)

Within the following heatmaps, exons are highlighted with gray background while introns are given in white. Predicted interaction sites are drawn in colored boxes where darker boxes relate to lower energy (more stable and probable) interactions. The x-axis corresponds to pre-mRNA indices while the y-axis represents positions of U1. For the latter, the U1 recognition site for intronic 5' splice sites is at position 3-10. Thus, interactions of that site correspond to the bottom of the graph. The top graph represents interaction sites without SHAPE constraints while the bottom graph depicts the altered prediction when U1 SHAPE constraints are considered within IntaRNA's accessibility computation. 

The left barplot shows the predicted interaction probabilities of all intronic 5' splice sites with the recognition site of U1 (called a *spot*). Blue bars represent the unconstrained probabilities while orange bars depict the probabilities when U1 SHAPE constraints are used.
The right bar plot provides the ratio of both probabilities for each interaction site (spot).

For further details, please refer to the manuscript.

The following plots are computed using
- IntaRNA v2.2.0 linking
- Vienna RNA package v2.4.7

## ACT1

![U1 interactions with ACT1](./data/ACT1/heatmap_ACT1-ENSRNA049495626-T1-U1.png)

![U1 interactions with ACT1](./data/ACT1/barplot_ACT1-ENSRNA049495626-T1-U1.png)


## NBR1

![U1 interactions with NBR1](./data/NBR1/heatmap_NBR1-ENSRNA049495626-T1-U1.png)

![U1 interactions with NBR1](./data/NBR1/barplot_NBR1-ENSRNA049495626-T1-U1.png)


## RPL16A

![U1 interactions with RPL16A](./data/RPL16A/heatmap_RPL16A-ENSRNA049495626-T1-U1.png)

![U1 interactions with RPL16A](./data/RPL16A/barplot_RPL16A-ENSRNA049495626-T1-U1.png)


## RPS9

![U1 interactions with RPS9](./data/RPS9/heatmap_RPS9-ENSRNA049495626-T1-U1.png)

![U1 interactions with RPS9](./data/RPS9/barplot_RPS9-ENSRNA049495626-T1-U1.png)


## RPS10

![U1 interactions with RPS10](./data/RPS10/heatmap_RPS10-ENSRNA049495626-T1-U1.png)

![U1 interactions with RPS10](./data/RPS10/barplot_RPS10-ENSRNA049495626-T1-U1.png)





