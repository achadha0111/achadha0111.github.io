---
title: "Paper dive: Transcriptomic reprogramming for neuronal age reversal"
date: 2025-01-20T05:34:39Z
draft: true
tags: [longevity, neuroscience, high throughput screens]
categories: []
math: true
summary: Deep dive into epigenetic and transcriptomic reprogramming to reverse aging in cells.
---

Sometimes you read a paper that substantially alters your views on the possibilities of science and you get this insatiable desire to dig 
into every detail of that paper. 
[Plesa et al.'s Transcriptomic reprogramming for neuronal age reversal](https://pubmed.ncbi.nlm.nih.gov/37004545/) is one such paper 
(borne out of the lead author's PhD thesis available [here](https://dash.harvard.edu/handle/1/37373691)).

The paper's key claim is that reversing aging of neurons is a viable strategy to prevent the occurence of major age related disorders, 
such as neurodegenerative diseases. It then lays out key observations, including those dating back to the 60s, that suggest that such age 
reversal can have major therapeutic implications by undoing significant damage done to the cell's epigenome and transcriptome. It highlights
that discovering such transcriptomic reprogramming factors for the neuronal cells will require:

1. Development of aging assays.
2. Identification of model in-vitro test platforms.
3. High throughput screens on a reasonable number of cells ($~10^6$) to identify agents to perturb gene
regulatory networks.

I want to explore these assertions in the context of establishing open questions, key experiments, competing approaches and a strategy to
navigate the regulatory landscape that such a therapy might enter. I also want to use it to further my own understanding
of the key technologies used in biotech - single cell sequencing, multiomics and assay development.

The central premise here is that we can avoid costs of age-related disorders by reversing the process of aging itself by correcting the cellular
dysfunction that typically occurs due to it. A cell's structure and function is a consequence of its gene expression and instabilities in this process
lead to dysfunction, such as that of aging. Gene expression is effectively described by the transcriptome which can be read and written to and therefore
is the ideal reprogramming target. This assertion is also my central gripe with 
this paper - what makes the transcriptome a better intervention point than the epigenome? My very rudimentary understanding suggests that even though
neurons don't divide and therefore do not need heritable epigenetic changes, transcription instabilities will still exist due to the unmodified epigenome.
I ask this as the transcriptome is controlled by the epigenome and companies 
like [NewLimit](https://www.newlimit.com) are developing epigenetic reprogramming drugs (although their first target is the liver). Is it harder
to read the epigenome of a cell compared to the transcriptome? Evidence certainly suggests so. I'll come back to this point as it requires a deeper comparison
of both the read and write techniques.








