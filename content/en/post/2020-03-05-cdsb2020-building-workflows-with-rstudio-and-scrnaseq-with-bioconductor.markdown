---
authors: ["admin"]
date: 2020-03-05 13:30:00+00:00
slug: cdsb2020-building-workflows-with-rstudio-and-scrnaseq-with-bioconductor
title: "CDSB Workshop 2020: Building workflows with RStudio and Bioconductor for single cell RNA-seq analysis"
categories: ["Events", "rstats"]
featured: true
---

#### Community of Bioinformatics Software Developers
 	
  * Workshop webpage: [https://comunidadbioinfo.github.io/post/cdsb2020-building-workflows-with-rstudio-and-scrnaseq-with-bioconductor/](https://comunidadbioinfo.github.io/post/cdsb2020-building-workflows-with-rstudio-and-scrnaseq-with-bioconductor/)

 	
  * Level: **intermediate - advanced**

 	
  * Language: **English**

 	
  * When: August 3 - August 7, 2020

 	
  * Where: A [LCG-UNAM](https://www.lcg.unam.mx/) classroom inside the [Center for Genomic Sciences](http://www.ccg.unam.mx/en), Cuernavaca, Morelos, Mexico

 	
  * Twitter: [@CDSBMexico](https://www.twitter.com/CDSBMexico/)

 	
  * Facebook: [@CDSBMexico](https://www.facebook.com/CDSBMexico/)

 	
  * GitHub: [https://github.com/ComunidadBioInfo/cdsb2020](https://github.com/ComunidadBioInfo/cdsb2020)

 	
  * [Registration](http://congresos.nnb.unam.mx/) (Will open on April XX, 2020)


## **Summary**

Join us for our 2020 workshop! This year we’ll teach you how to improve your skills for interacting with the R programming language with diverse strategies for organizing your code and projects. This will help you document your analyses such that they are easily to reproduce and for sharing them with your collaborators (from academia to industry). As a use case, we will learn the statistical tools needed for analyzing single cell transcriptomics (scRNA-seq) data using Bioconductor. Completing this workshop will help you in all your R projects and your analyses of biological data: all your analyses will benefit from the organization skills and the ideas behind scRNA-seq are used in many bioinformatics projects. Besides the CDSB instructors, thanks to Bioconductor this year we will count with [Robert Amezquita](https://comunidadbioinfo.github.io/authors/robamezquita/), co-author of the book [_Orchestrating Single Cell Analysis with Bioconductor_](https://osca.bioconductor.org/) that was published by _Nature Methods_ ([DOI](https://doi.org/10.1038/s41592-019-0654-x)), that is among the [most publicized papers](https://www.altmetric.com/details/71569824) in 2020.

<iframe src="https://giphy.com/embed/L40sNfcoJs5Op5afQU" width="480" height="240" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/hustlersmovie-hustlers-movie-hustler-L40sNfcoJs5Op5afQU">via GIPHY</a></p>

## **Requirements**

**Requirements prior knowledge**

* Participants should have basic to intermediate knowledge of the R programming language: variable assignment, reading files: `read.csv`; data structures: `matrix`, `data.frame`, `list`; data types: `character`, `numeric`, `factor`, `logical`, etc; installation and use of packages.
* Know how to use RStudio.
* Be interested in learning good practices for organizing your work and sharing your work with others.
* Be interested in learning how to analyze biological data using R/Bioconductor packages.



**Technical requirements**

* Personal computer. Minimum 8GB RAM, a mouse and sufficient disk space for text files and image files. Administrator privileges to install and run utilities such as RStudio.



## **Overview**

In recent years, [R](https://cran.r-project.org/) has become one of the most used programming languages for data science. The explosion in data available in many fields has increased the demand for data analysts, which is the case in Bioinformatics. `R` users start by learning how to use the tools others have openly shared with the international community. These `R` users acquire skills as they continue to analyze data and might even start to interact with `R` software developers through community websites such as [RStudio Community](https://community.rstudio.com/), [Bioconductor Support](https://support.bioconductor.org/) or via Twitter using the [#rstats hashtag](https://twitter.com/search?q=%23rstats). Eventually some `R` users will want to write their own functions and organize their code across several projects. It is at this point that it’s useful to learn how to organize your code in order to make your life as an R programmer easier, such that you spend more time on your projects instead of remembering where your code is or what you did a few weeks ago. In order to practice these concepts, we will review the most recent methods for analyzing single cell RNA sequencing (scRNA-seq) data using R packages specialized for this goal that are freely available through [Bioconductor](https://bioconductor.org).

The instructors of this workshop have participated at CDSB since its foundation and have gone to conferences such as [BioC2019](http://bioc2019.bioconductor.org/) and [rstudio::conf(2020)](https://resources.rstudio.com/rstudio-conf-2020), among others. In recent years we taught how to make R and Bioconductor packages, which are of great use for sharing code with others. Recently, CDSB alumni sent their [first R package to Bioconductor](https://comunidadbioinfo.github.io/post/from-bioconductor-users-to-developers-our-first-community-submission/), which represented a huge percent increase of Latin American representation in the Bioconductor developers community, thus demonstrating that participating at a CDSB workshop has an impact beyond the one week workshop. For 2020 we will have an applied focus while maintaining our goals at CDSB which are:

 	
  1. Turn (bioinformatics) software users into (bioinformatics) software developers.

 	
  2. Foster the exchange of expertise and establish multidisciplinary collaborations.

 	
  3. Create a community of Latin American scientists committed to the development of software and computational pipelines for (biological) data analysis.

 	
  4. Help train users that can become local instructors and continue to grow their local communities.

Besides the CDSB instructors, thanks to Bioconductor this year we will count with [Robert Amezquita](https://comunidadbioinfo.github.io/authors/robamezquita/), co-author of the book [_Orchestrating Single Cell Analysis with Bioconductor_](https://osca.bioconductor.org/) that was published by _Nature Methods_ ([DOI](https://doi.org/10.1038/s41592-019-0654-x)), that is among the [most publicized papers](https://www.altmetric.com/details/71569824) in 2020. That is why the CDSB 2020 workshop will be taught in English.

This workshop is part of a long-term project to create a community of developers from Latin America. We hope to hold regular meetings in the future (similar to BioC, EuroBioc and BioCAsia) where attendees present their own software contributions. To provide a welcoming environment please follow our [code of conduct](https://comunidadbioinfo.github.io/codigo-de-conducta/).





## **Program**

5 days, 8 hours each of workshop plus breaks and meals. For the detailed schedule check [the workshop repository cdsb2020](https://github.com/ComunidadBioInfo/cdsb2020).


Day 1

* Workflow around RStudio projects:
- Working with projects against scripts.
- Creating a project.
- Using safe paths.
- How should I name my file?

Day 2

* Using Git and GitHub.
* CDSB community building activity.
* Writing and documenting functions.
* Debugging R code.

Day 3

* Good practice for configuring and maintain workspaces.
* Installing R packages from source.
* General overview of single cell RNA-seq (scRNA-seq) data processing
* RNA-seq against scRNA-seq: how different is the data? 

Day 4 

* SingleCellExperiment R objects.
* Exploratory data analysis of scRNA-seq data.
* Dimension reduction methods.
* Identifying gene cell markers.

Day 5

* Classifying into cell types.
* Batch effects in scRNA-seq experiments.
* Differential analyses with scRNA-seq data (cell type proportions, differential expression, differential biological variation).



## **Instructors**

- [Alejandra Medina-Rivera](http://comunidadbioinfo.github.io/authors/amedina/) (International Laboratory for Human Genome Research, Juriquilla, Querétaro, Mexico) Alejandra recently presented a [keynote at the Women in Data Science](https://twitter.com/MxPyladies/status/1233208231184543745?s=20) event in Mexico City.

- [Joselyn Chávez](http://comunidadbioinfo.github.io/authors/josschavezf) (IBT-UNAM, Cuernavaca, Morelos, Mexico). Joselyn presented her work at [BioC2019](http://bioc2019.bioconductor.org/) thanks to a travel award, attended [rstudio::conf(2020)](https://resources.rstudio.com/rstudio-conf-2020) thanks to a diversity scholarship where she took the _What They Forgot to Teach You about R_ workshop, and recently was part of the [first `R` package submission to Bioconductor by CDSB alumni](https://comunidadbioinfo.github.io/post/from-bioconductor-users-to-developers-our-first-community-submission/). She initially was a CDSB2018 student.

- [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) (Lieber Institute for Brain Development, Baltimore, MD, USA). Leonardo recently published a [pre-print on spatial transcriptomics using 10xGenomics Visium data](https://twitter.com/fellgernon/status/1233661576433061888?s=20).

- [Maria Teresa Ortiz](http://comunidadbioinfo.github.io/authors/mteresa/) (CONABIO and ITAM, Mexico). Teresa presented at [rstudio::conf(2020)](https://resources.rstudio.com/rstudio-conf-2020) her work on fast counting algorithms for Mexican presidential elections.

- [Robert Amezquita](https://comunidadbioinfo.github.io/authors/robamezquita/) (Fred Hutchinson Cancer Research Center, Seattle, WA, USA) Lead author of the book [_Orchestrating Single Cell Analysis with Bioconductor_](https://osca.bioconductor.org/) that was published by _Nature Methods_ ([DOI](https://doi.org/10.1038/s41592-019-0654-x)), that is among the [most publicized papers](https://www.altmetric.com/details/71569824) in 2020. Robert taught a workshop on this topic at [BioC2019](http://bioc2019.bioconductor.org/).

## **Organizing committee**

- [Alejandra Medina-Rivera](http://comunidadbioinfo.github.io/authors/amedina/) (International Laboratory for Human Genome Research, Juriquilla, Querétaro, Mexico)
  
- [Alejandro Reyes](http://comunidadbioinfo.github.io/authors/areyes/) (Dana-Farber Cancer Institute, Boston, MA, USA)

- [Joselyn Chávez](http://comunidadbioinfo.github.io/authors/josschavezf) (IBT-UNAM, Cuernavaca, Morelos, Mexico)

- [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) (Lieber Institute for Brain Development, Baltimore, MD, USA)


## **[Code of Conduct](../../codigo-de-conducta/)**



## **Sponsors**


[Become our **sponsor**](../../niveles-de-patrocinio/)


| | | | |
| --- | --- | --- | --- |
| [![Centro de Ciencias Genómicas UNAM](/img/CCG_Logo_HR-300x114.png)](http://www.ccg.unam.mx) | [![](/img/LCG_Logo_HR-white.png)](http://www.lcg.unam.mx) | [ <img src="http://bioconductor.org/images/logo/jpg/bioconductor_logo_cmyk.jpg" width="250px">](http://bioconductor.org/) | 

<!-- [![](/img/RConsortium_Horizontal_Pantone-768x173.png)](https://www.r-consortium.org/) | -->

CDSB is a node of the [Mexican Bioinformatics Network (RMB in Spanish)](https://www.redmexicanadebioinformatica.org/) and jointly organizes the yearly workshop with the [National Node of Bioinformatics (NNB)](http://www.nnb.unam.mx/).


