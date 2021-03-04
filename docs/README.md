---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: e15-4yp-Optimizing-Mitochondria-Genome-Assembly-And-Annotation
title: Optimizing the procedure of mitochondrial genome assembly and annotation
---



[comment]: # "This is the standard layout for the project, but you can clean this and use your own template"

# Project Title

#### Team

- E/15/330, K.Sathurshan, [email](mailto:name@email.com)
- E/15/366, S.Thinesh, [email](mailto:name@email.com)
- E/15/373, R.Vaheesan, [email](mailto:name@email.com)
#### Supervisors

- Dr. Asitha Bandaranayake, [email](mailto:asithab@eng.pdn.ac.lk)
- Prof. Pradeepa Bandaranayake, [email](mailto:pradeepag@agri.pdn.ac.lk)

#### Table of content

1. [Abstract](#abstract)
2. [Related works](#related-works)
3. [Methodology](#methodology)
4. [Experiment Setup and Implementation](#experiment-setup-and-implementation)
5. [Results and Analysis](#results-and-analysis)-
6. [Conclusion](#conclusion)
7. [Publications](#publications)
8. [Links](#links)

---

## Abstract
Genome sequencing and genome assembly are the computational process of converting the sequence composition of the gene within the cell of an organism in a human readable form. Mitochondria is an important genome in the cell and there is a need to study this genome for various reasons.
The process of determining the order of bases A,G,T,C in the genome is known as genome sequencing.While sequencing the genome the original genome is separated into huge number of small parts known as reads and the end results of sequencing is a huge pool of reads(strings of A,G,T,C).These reads must be assembled back in a computer so that a biologist can identify and annotate the functionality of it.
There are several techniques were developed to sequence the genome,
the modern approach is next generation sequencing.
Ilumina sequencing is one of the broadly used next generation sequencing method and this method produce large number of high precision sequencing  short reads whereas other older methods produce longer reads.So the computational complexity of assembling back this large amount of read is high but cost efficient.
Here we mainly discuss on low coverage sequencing data assembly.The sequencing data consist of multiple copies of same genome in low coverage data the number of copies are relatively lower than high coverage data.

There are several problems faced by biologists while and after assembling genome like low accurate assembly of genome and slow assembly process. In this report we address these problems and proposing optimal solution to these problems, in addition to these generic problems this project also focus on mitochondria genome extraction from whole genome sequencing data and working with skim sequenced low coverage data.

Before developing the pipeline for genome assembly the existing tools for genome assembly were studied.This report contain a review of those tools and in future it was planned to recommend biologists optimal tools for their type of assembly. The implementation plan and the steps done to assemble  Cinnamomum verum(Ceylon cinnamon tree)- genome is discussed here.Finally an implementation plan for developing a new pipeline for optimize mitochondria genome assembly and annotation is stated.

## Related works
There are several assembly pipelines suggested for assembling genome, below are the narrow downed pipelines/ tools used for mitochondrial genome assembly. There are two common approaches for assembly genome one is De novo assembly another one is Reference based alignment.Some tools use one of these approaches and some use hybrid approach consisting both.

Here let's discuss the tools that are used specifically for mitochondrial genome assembly

1.NovoPlasty
In NOVOPlasty there is a way to assemble genome from skim sequenced data, we can either assemble a whole organelle genome or isolate mitochondrial genome first and assemble it later. The best strategy for assembling depends on available data-set,computational power and reference genome availability. This tool uses a new algorithm to do the de novo assembly which is known as seed-extension, by this method NOVOPlasty claims that it assemble genome as accurate as other reference based assemblers such as MITObim,MIRA,ARC,SOAPdenova2.
NOVOPlasty decreases computational complexity by storing the reads in a hash table and seed-extend it. As this tool claims it took 11 minutes duration and 15 GB memory to assemble 99.98% of G.intermedia mitochondrion genome with 100 % accuracy where MITObim took 4777 minutes,63.4 GB memory to assemble 99.95\% of genome with 99.93% accuracy and SOAPdenovo2 took  19 minutes,27 GB memory to assemble 99.98% of genome with 99.98% accuracy.
## Methodology

## Experiment Setup and Implementation

## Results and Analysis

## Conclusion

## Publications
1. [Semester 7 report](./)
2. [Semester 7 slides](./)
3. [Semester 8 report](./)
4. [Semester 8 slides](./)
5. Author 1, Author 2 and Author 3 "Research paper title" (2021). [PDF](./).


## Links

[//]: # ( NOTE: EDIT THIS LINKS WITH YOUR REPO DETAILS )

- [Project Repository](https://github.com/cepdnaclk/repository-name)
- [Project Page](https://cepdnaclk.github.io/repository-name)
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)

[//]: # "Please refer this to learn more about Markdown syntax"
[//]: # "https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet"
