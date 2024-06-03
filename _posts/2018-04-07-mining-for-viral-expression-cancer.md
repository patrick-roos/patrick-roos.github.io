---
layout: post
title: Mining for Viral Expression in Human Cancer
date: 2018-04-07 12:34:00
description:
tags: data-mining, bioinformatics, cancer
categories:
featured: false
---

Human papillomavirus (HPV) is known to be linked to cervical cancers in humans, and luckily HPV vaccines have become fairly common. What viruses in general play a role in cancers, and to what extent, is still a somewhat open question. The vast amount of cancer and virus genomic datasets we have at the National Cancer Institute through programs like the <a href="https://www.cancer.gov/ccg/research/genome-sequencing/tcga">Cancer Genome Atlas Program</a> (TCGA) and <a href="https://www.ncbi.nlm.nih.gov/labs/virus/vssi/#/">NCBI Virus</a>, combined with sequence alignment and classification software like <a href="https://bowtie-bio.sourceforge.net/bowtie2/index.shtml">Bowtie 2</a> or <a href="https://ccb.jhu.edu/software/kraken/">Kraken</a> developed by colleagues at John's Hopkins University presented a great opportunity to explore this question further and help solidify some answers.

With these resources, we analyzed large cancer genomic datasets for microbial DNA and RNA expression to check for correlations between various virus expression patterns in cancer vs. normal tissue, including cervical, ovarian, lung, and brain cancers. Our findings indicated that while the correlation of HPV and cervical cancer was by far the clearest, which was no surprise, there was some significant prevalence of HPV in North American cases of ovarian cancer.

For more info see the full paper: <a href="https://pubmed.ncbi.nlm.nih.gov/25721614/">In North America, some ovarian cancers express the oncogenes of preventable human papillomavirus HPV-18</a>.
