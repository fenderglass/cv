---
permalink: /
title: ""
excerpt: "Bio"
author_profile: true
---

Bio
===

I am a Postdoctoral Fellow at the University of California San Diego, 
co-suprevised by [Rob Knight](https://knightlab.ucsd.edu/) and 
[Pavel Pevzner](https://bioalgorithms.ucsd.edu/). I completed my PhD in September 2019 
in the [Computer Science and Engineering Depertment](https://cse.ucsd.edu/) 
at UCSD, under the mentorship of Pavel Pevzner.

My research focus is bioinformatics. In particular, I am interested in algorithms
for genome assembly using long reads, which enable high-quality reconstruction
of the human genome sequence. I also work on tools for comparative genomics and computational proteomics.

Research projects
=================


<img src="../images/flye_graph.png" alt="Flye Graph" style="width:20%;" align="left"/>
**Long-read assembly using Flye and metaFlye**. 
The new long-read sequencing technologies (such as Pacific Biosciences or Oxford Nanopore)
increased the read length up to tens of thousands of nucleotides, and substantially improved
the quality of many genome assemblies. These technologies, however, are facing the challenge
of the high read errors. We have created the [Flye](https://github.com/fenderglass/Flye) algorithm
for assembly of long and error-prone reads to address this challenge.
Flye is using the novel [repeat graph framework](https://www.nature.com/articles/s41587-019-0072-8),
which enables fast and accurate assemblies of various organisms. In particular,
Flye is good for assembly of human genomes using ultra-long Oxford Nanopore sequencing data 
(such as [NA12878](https://github.com/nanopore-wgs-consortium/NA12878) or 
[CHM13](https://github.com/nanopore-wgs-consortium/CHM13)).
We are now working on the new [metaFlye](https://www.biorxiv.org/content/10.1101/637637v1) 
algorithm for metagenome assembly using long reads. 

We develop the long-read assmebly methods with the help of our collaborators from 
[Rob Knight's lab](https://knightlab.ucsd.edu/), 
[T2T consortium](https://sites.google.com/ucsc.edu/t2tworkinggroup), 
[Tim Smith's lab](https://www.ars.usda.gov/plains-area/clay-center-ne/marc/gbahru/people/timothy-smith/), 
[JGI](https://jgi.doe.gov/) and many others.

Watch our Flye assembler presentation and discussion hosted by [Long Read Club](https://www.longreadclub.org/):
<div class="iframe-container" style="width:60%;">
<iframe width="280" height="156" src="https://www.youtube.com/embed/It5KXnPBnbg" frameborder="20" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<hr>

<img src="../images/Ragout.jpg" alt="Ragout" style="width:30%;" align="left"/>
**Comparative assembly using multiple references**. 
Since many de novo assemblies of large genomes are still incomplete, one
can use the information for related referece genomes to order and orient
the contig fragments. We have developed [Ragout](https://github.com/fenderglass/Ragout)
that infers structural rearrangements between the multiple input refences and 
reconstructs the most probable architecture of a target genome. 
We used Ragout to produce [chromosome assemblies](https://genome.cshlp.org/content/28/11/1720.short) 
of multiple [mice genomes](https://www.nature.com/articles/s41588-018-0223-8), 
which gave insights into rodent genome evolution and novel functional loci.
Mouse assemblies were generated as a part of 
[Mouse genomes sequencing project](https://www.sanger.ac.uk/science/data/mouse-genomes-project),
hosted by Wellcome Sanger Institute.

<hr>

<img src="../images/syntenypaths.png" alt="Synteny Paths" style="width:25%;" align="left"/>
**Tools for assembly graphs analysis**.The analysis of genome graphs is helpful 
in studying repeat structure of genomes (for example, mosaic segmental 
duplications in humans). To visualize large and complex assembly graphs,
we developed [AGB](https://academic.oup.com/bioinformatics/article-abstract/35/18/3476/5306331/) - 
an interactive graph visualization [tool](https://github.com/almiheenko/AGB). 
We have also introduced a new [Synteny Paths](http://drops.dagstuhl.de/opus/volltexte/2019/11054/) 
approach for [comparison](https://github.com/epolevikov/Asgan) 
of two related genomes in a graph from, similarly
to synteny block for linear genomes. The tools were developed in a collaboration
with the [Center for Algorithmic Biotechnology](http://cab.spbu.ru/) and
[Bioinformatics Institute](https://bioinf.me/en) in St. Petersburg, Russia.

