---
authors: ["admin"]
date: 2020-03-05 13:30:00+00:00
slug: cdsb2020-building-workflows-with-rstudio-and-scrnaseq-with-bioconductor
title: "CDSB Workshop 2020: Building workflows with RStudio and Bioconductor for single cell RNA-seq analysis"
categories: ["Events", "rstats"]
featured: true
---

_This workshop is part of the [Mexican Bioinformatics Encounter (EBM in Spanish) 2020](http://www.nnb.unam.mx/TIB2020/) organized by CDSB with:_

| TIB2020 | RMB | NNB | CCG-UNAM |
| --- | --- | --- | --- |
| [<img src="http://www.nnb.unam.mx/TIB2020/wp-content/uploads/sites/2/2020/03/TIF-Logo_2020.png" width="150px" />](http://www.nnb.unam.mx/TIB2020/) | [<img src="http://www.nnb.unam.mx/TIB2020/wp-content/uploads/sites/2/2020/03/RMB_Logo-horizontal.png" width="150px" />](https://www.redmexicanadebioinformatica.org/) | [<img src="http://www.nnb.unam.mx/TIB2020/wp-content/uploads/sites/2/2020/03/logo-principal.png" width="150px" />](http://www.nnb.unam.mx/) | [<img src="http://www.nnb.unam.mx/TIB2020/wp-content/uploads/sites/2/2020/03/CCG_Logo_HR.png" width="150px" />](http://www.ccg.unam.mx/) |

#### Community of Bioinformatics Software Developers (CDSB)
 	
  *  [Workshop webpage](https://comunidadbioinfo.github.io/post/cdsb2020-building-workflows-with-rstudio-and-scrnaseq-with-bioconductor/)

 	
  * Level: **intermediate - advanced**

 	
  * Language: **Spanish**

 	
  * When: August 3 - August 7, 2020 (9 am to 5:30 pm, Friday until 2:30 pm)

 	
  * Where: Online through the Zoom platform. Hours are based on Mexico's central time zone.

 	
  * Twitter: [@CDSBMexico](https://www.twitter.com/CDSBMexico/)

 	
  * Facebook: [@CDSBMexico](https://www.facebook.com/CDSBMexico/)

 	
  * GitHub: [https://github.com/ComunidadBioInfo/cdsb2020](https://github.com/ComunidadBioInfo/cdsb2020)

 	
  * [Registration](http://www.nnb.unam.mx/TIB2020/)


## **Summary**

Join us for our 2020 workshop! This year we’ll teach you how to improve your skills for interacting with the R programming language with diverse strategies for organizing your code and projects. This will help you document your analyses such that they are easily to reproduce and for sharing them with your collaborators (from academia to industry). As a use case, we will learn the statistical tools needed for analyzing single cell transcriptomics (scRNA-seq) data using Bioconductor. Completing this workshop will help you in all your R projects and your analyses of biological data: all your analyses will benefit from the organization skills and the ideas behind scRNA-seq are used in many bioinformatics projects.

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
  
The scRNA-seq portion of the workshop will be based on the book [_Orchestrating Single Cell Analysis with Bioconductor_](https://osca.bioconductor.org/) that was published by _Nature Methods_ ([DOI](https://doi.org/10.1038/s41592-019-0654-x)) and is among the [most publicized papers](https://www.altmetric.com/details/71569824) in 2020.

This workshop is part of a long-term project to create a community of developers from Latin America. We hope to hold regular meetings in the future (similar to BioC, EuroBioc and BioCAsia) where attendees present their own software contributions. To provide a welcoming environment please follow our [code of conduct](https://comunidadbioinfo.github.io/codigo-de-conducta/).





## **Program**

9 am to 5:30 pm on Mexico's central time zone (Friday we end at 2:30 pm) with breaks and time to eat. The detailed schedule and the Zoom links will be provided to those participants that register for the event through the private CDSB Google Calendar. For more schedule details check [the CDSB2020 workshop GitHub repository](https://github.com/ComunidadBioInfo/cdsb2020).


Every day we will have a help session from 8 to 9 am for those that need help installing the required software for the workshop.

Day 1

* EBM2020 inauguration
* Welcome to CDSB
* Participants self introductions
* Workflow around RStudio projects:
  - Introduction to the project-oriented workflow.
  - Working with projects against scripts.
  - Creating a project.
  - Using safe paths.
  - How should I name my file?

Day 2

* Using Git and GitHub.
* Modifying the R startup files.
* Writing and documenting functions.
* Debugging R code.

Day 3

* Good practice for configuring and maintain workspaces.
* Remote picture / video.
* Installing R packages from source.
* General overview of single cell RNA-seq (scRNA-seq) data processing
* Community-building activities
* Overview of the scRNA-seq material

Day 4 

* Introduction to scRNA-seq
* Introduction to scRNA-seq with Bioconductor
* Data infrastructure and data import
* Quality control
* Data normalization

Day 5

* Feature selection
* Dimension reduction
* Clustering and differential gene expression analysis
* spatialLIBD: analyzing data from the Visium assay by 10x Genomics
* Workshop evaluation
* Closing ceremony and CDSB reminders



## **Instructors**

- [Alejandra Medina-Rivera](http://comunidadbioinfo.github.io/authors/amedina/) (International Laboratory for Human Genome Research, Juriquilla, Querétaro, Mexico) Alejandra recently presented a [keynote at the Women in Data Science](https://twitter.com/MxPyladies/status/1233208231184543745?s=20) event in Mexico City.

- [Alejandro Reyes](http://comunidadbioinfo.github.io/authors/areyes/) (Data Scientist, Novartis, Basel, Switzerland). Alejandro recently worked on the [regutools](http://bioconductor.org/packages/regutools) project with CDSB alumni that was published at [Oxford Bioinformatics](https://academic.oup.com/bioinformatics/article-abstract/doi/10.1093/bioinformatics/btaa575/5861528?redirectedFrom=fulltext).

- [Joselyn Chávez](http://comunidadbioinfo.github.io/authors/josschavezf) (IBT-UNAM, Cuernavaca, Morelos, Mexico). Joselyn presented her work at [BioC2019](http://bioc2019.bioconductor.org/) thanks to a travel award, attended [rstudio::conf(2020)](https://resources.rstudio.com/rstudio-conf-2020) thanks to a diversity scholarship where she took the _What They Forgot to Teach You about R_ workshop, and recently was part of the [first `R` package submission to Bioconductor by CDSB alumni](https://comunidadbioinfo.github.io/post/from-bioconductor-users-to-developers-our-first-community-submission/). She initially was a CDSB2018 student.

- [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) (Lieber Institute for Brain Development, Baltimore, MD, USA). Leonardo recently published a [pre-print on spatial transcriptomics using 10xGenomics Visium data](https://twitter.com/lcolladotor/status/1233661576433061888?s=20).

- [Marcel Ramos Perez](http://comunidadbioinfo.github.io/authors/mramos/) (Roswell Park Comprehensive Cancer Center and CUNY School of Public Health, USA). Marcel is part of the [Bioconductor Core Team](http://bioconductor.org/about/core-team/) and is the author of many Bioconductor packages including [MultiAssayExperiment](http://bioconductor.org/packages/MultiAssayExperiment).

- [Maria Teresa Ortiz](http://comunidadbioinfo.github.io/authors/mteresa/) (CONABIO and ITAM, Mexico). Teresa presented at [rstudio::conf(2020)](https://resources.rstudio.com/rstudio-conf-2020) her work on fast counting algorithms for Mexican presidential elections.

## **Organizing committee**

- [Alejandra Medina-Rivera](http://comunidadbioinfo.github.io/authors/amedina/) (International Laboratory for Human Genome Research, Juriquilla, Querétaro, Mexico)
  
- [Alejandro Reyes](http://comunidadbioinfo.github.io/authors/areyes/) (Data Scientist, Novartis, Basel, Switzerland)

- [Joselyn Chávez](http://comunidadbioinfo.github.io/authors/josschavezf) (IBT-UNAM, Cuernavaca, Morelos, Mexico)

- [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) (Lieber Institute for Brain Development, Baltimore, MD, USA)


## **[Code of Conduct](../../codigo-de-conducta/)**



## **Sponsors**

[Become our **sponsor**](../../niveles-de-patrocinio/)

### Platinum level

### Gold level

### Silver level

[<img src="http://bioconductor.org/images/logo/jpg/bioconductor_logo_cmyk.jpg" width="250px">](http://bioconductor.org/)

[<img src="/img/RConsortium_Horizontal_Pantone-768x173.png" width="250px">](https://www.r-consortium.org/)

## Organizers

CDSB is a node of the [Mexican Bioinformatics Network (RMB in Spanish)](https://www.redmexicanadebioinformatica.org/) and jointly organizes the yearly workshop with the [National Node of Bioinformatics (NNB)](http://www.nnb.unam.mx/).

[<img src="http://www.nnb.unam.mx/TIB2020/wp-content/uploads/sites/2/2020/03/TIF-Logo_2020.png" width="250px" />](http://www.nnb.unam.mx/TIB2020/)

[<img src="http://www.nnb.unam.mx/TIB2020/wp-content/uploads/sites/2/2020/03/RMB_Logo-horizontal.png" width="250px" />](https://www.redmexicanadebioinformatica.org/)

[<img src="http://www.nnb.unam.mx/TIB2020/wp-content/uploads/sites/2/2020/03/logo-principal.png" width="250px" />](http://www.nnb.unam.mx/)


[<img src="http://www.nnb.unam.mx/TIB2020/wp-content/uploads/sites/2/2020/03/CCG_Logo_HR.png" width="250px" />](http://www.ccg.unam.mx/)

With support from:

[<img src="http://www.nnb.unam.mx/TIB2020/wp-content/uploads/sites/2/2020/03/LCG_Logo_HR-white-e1522778427811.png" width="250px" />](https://www.lcg.unam.mx/)

[<img src="https://www.zaragoza.unam.mx/portal/wp-content/Portal2015/Descargas/logo_unam_azul.jpg" width="250px">](http://www.unam.mx/)
