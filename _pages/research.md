---
layout: archive
title: "High resolution, multi-omic network biology"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Overview
My lab uses high resolution (single cell RNA-seq, spatial transcriptomics), multi-omic (transcriptomics, metabolomics, and epigenomics) and biological networks (signaling networks, metabolic networks) to address a wide range problems in stem cell biology, cancer and aging.  

## 1. Catching the wisphers in single cell transcriptomics   
I recently developed a method called talklr (intercellular cross**TALK** using **L**igand-**R**eceptor), which uses Kullback-Leibler divergence, a concept from inforamtion theory, to uncover interesting ligand-receptor interactions among multiple cell types in single cell RNA-seq data. talklr can automatically detect ligand-receptor pairs mediating one-to-many or many-to-many cell-cell interactions. It also uncovers interesting ligand-receptor re-wiring between two conditions (e.g., disease vs. healthy, young vs. old).  
* Paper: [talklr uncovers ligand-receptor mediated intercellular crosstalk](https://www.biorxiv.org/content/10.1101/2020.02.01.930602v2)
* Interactive website (no programming experiences needed): [hosted on Shiny app](https://yuliangwang.shinyapps.io/talklr/)
* R package, so it can be easily integrated into existing scRNA-seq workflows, [available at Github](https://github.com/yuliangwang/talklr/)  

## 2. Genome-scale metabolic network modeling of the tumor microenvironment   
Spatially resolved transcriptomics data is increasingly used to profile many diseases (e.g., prostate cancer, breast cancer, melanoma, prostate cancer, ALS) and developmental processes (e.g., embryogenesis, heart development). We developed a new computational pipeline that uses the [mCADRE method](https://bmcsystbiol.biomedcentral.com/articles/10.1186/1752-0509-6-153) I previously developed to build spatially-resolved metabolic network models of the prostate cancer microenvironment. We identified novel selective metabolic targets that would otherwise be missed by models built from bulk transcriptomics data. 
* Paper: [Spatial modeling of prostate cancer metabolic gene expression reveals extensive heterogeneity and selective vulnerabilities](https://www.nature.com/articles/s41598-020-60384-w) 

## 3. Using scRNA-seq to identify maturation signatures of pluripotent stem cell derived cardiomyocytes (PSC-CM)
My collaborators at ISCRM developed a microRNA cocktail to accelerate the maturation of PSC-CM. I performed scRNA-seq analysis of PSC-CM with different microRNA over-expression/knock-out combinations to determine which ones are driving the maturation process. We evaluated our discovery against publicly available bulk and single cell RNA-seq of human & mouse heart development. I also used trajectory analysis to uncover an interesting subset of proliferating PSC-CMs that emerged after knocking out a key component of the mitochondria fatty acid oxidation machinery. This mimics the genetic defects in sudden infant deaths. Our collaborators succesfully identified a small molecule that mitigate this defect in vitro. 
* Paper: [TFPa/HADHA is required for fatty acid beta-oxidation and cardiolipin re-modeling in human cardiomyocytes](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6789043/)
* Additional paper using bulk RNA-seq to assess effects of fatty acid on maturation: [Fatty Acids Enhance the Maturation of Cardiomyocytes Derived from Human Pluripotent Stem Cells](https://www.sciencedirect.com/science/article/pii/S2213671119303078). 
* For more background information, please checkout our review paper: [Metabolic remodeling in early development and cardiomyocyte maturation](https://www.sciencedirect.com/science/article/pii/S1084952116300489).




