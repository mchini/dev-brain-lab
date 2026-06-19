---
title: iSTTC is out in PLOS Computational Biology!
date: 2026-03-17

image:
  preview_only: true
profile: false 
---
<div style="height: 14px;"></div>

I am thrilled to share that our paper introducing [iSTTC](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1013385) has just been published in *PLOS Computational Biology*!
This work was led by Irina Pochinok, who drove the project from start to finish with great dedication and rigor. Congratulations Irina, well deserved!

{{< figure src="featured.png" >}}

For those unfamiliar with iSTTC, here is the short version: intrinsic neural timescales reflect how neural networks integrate information over time.
They are short in brain areas specialized in rapid sensory reactions, and longer in those devoted to complex decision-making.
I find them fascinating because they are a promising bridge between low-level mechanisms — single-neuron or circuit properties — and high-level cognitive phenomena.
And they are remarkably robust: replicated across species as different as worms and humans, and across recording modalities from single-unit activity to fMRI.

The problem is that estimating timescales reliably from sparse or epoched spike data has always been tricky with existing methods.
iSTTC improves this: it provides accurate estimates even under challenging conditions, works on both continuous and trial-based data,
and substantially relaxes inclusion criteria — meaning you can include many more neurons in your analyses.
As a bonus, we discovered that the common practice of estimating timescales from short, epoched recordings leads to errors roughly ten times larger
than those from long, uninterrupted recordings. Not our original goal, but a finding we think the timescales community will care about.

I am particularly excited because our lab works a lot with early brain development, where spiking data is notoriously sparse —
exactly the regime where iSTTC shines. We built this tool with those datasets in mind, and I cannot wait to start applying it.

If you want to give it a try yourself, the code is freely available on [GitHub](https://github.com/iinnpp/isttc). We hope many of you will!

A heartfelt thank you to the editors and reviewers, whose feedback genuinely pushed the manuscript to a higher level.
One reviewer, in a fun twist, is no longer anonymous: I ran into him (and he presented himself) at a bar during COSYNE this year!

Finally, a well-deserved (if slightly ironic) acknowledgment to Piet Mondrian for the inspiration behind the iSTTC logo.
We like to think he would have approved, even though that's probably highly unlikely.
