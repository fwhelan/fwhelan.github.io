---
layout: post
title:  "New pangenome research up on bioRxiv"
date:   2020-11-11 08:08:27 +0100
categories: jekyll update
---
Since the sequencing of bacterial genomes started to become more common-place a few decades ago, we've recognized the vast genetic diversity that can exist within a species (or other group of closely related genomes). In prokaryotes, this is commonly attributed to pervasive horizontal gene transfer and the relative fluidity of the genome. This collective genetic diversity, termed "the pangenome", can be extensive (an "open" pangenome) or minimal ("closed"). This raises the question: what mechanisms govern the structure of pangenomes?

In new research posted to [bioRxiv][biorxiv], I - along with colleagues from [the McInerney group][mcinerney] - consider this question by  investigating gene-gene relationships within the pangenome of Pseudomonas sp. We use a piece of software we previously developed called [Coinfinder][coinfinder] to identify genes that significantly co-occur and avoid each other more often than we would expect by chance. We find that the vast majority (86.7%) of genes which vary from strain-to-strain form predictable co-occurrence and/or avoidance patterns with other genes, and that these gene pairs are more likely to share functionality, be co-transcribed, and encode proteins with known interactions. These findings suggest that the genetic variability within the pangenome, at least of this genus, is selected for, as opposed to being due to the effects of random genetic drift.

A draft of the manuscript is freely available on [bioRxiv][biorxiv], and all associated raw data and scripts used is available as [a github repository][repo]. Myself and my co-authors recognize that we've only scratched the surface of what could be investigated using this dataset; we've tried to be as explicit as possible in what we've made available with the hopes that it would be fairly straight forward for others to pick out their favourite gene, pathway, or clade for further analyses. If there is something that interests you, please work away or feel free to get in touch!

{:refdef: style="text-align: center;"}
![image](/assets/images/posts/network.svg){:width="600px" }
{: refdef}

[biorxiv]: https://www.biorxiv.org/content/10.1101/2020.10.28.359307v1
[mcinerney]: http://mcinerneylab.com/
[repo]: https://github.com/fwhelan/pseudomonas-manuscript 
