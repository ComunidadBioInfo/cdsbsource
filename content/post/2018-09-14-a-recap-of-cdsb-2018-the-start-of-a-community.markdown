---
author: Leonardo
date: 2018-09-14 02:13:22+00:00
link: http://www.comunidadbioinfo.org/a-recap-of-cdsb-2018-the-start-of-a-community/
slug: a-recap-of-cdsb-2018-the-start-of-a-community
title: 'A recap of CDSB 2018: the start of a community'
categories:
- rstats
---


Organizing an event is a lot of work, much more than you plan for it. But harvesting the fruits of a successful event makes the workload worth it.

In July, we kicked off the first [**Bioconductor Latin American Developers Workshop 2018**](http://www.comunidadbioinfo.org/r-bioconductor-developers-workshop-2018/) (_LatAmBioc2018_). The main goals of this meeting were to encourage the development of the Bioconductor project in Mexico and to start a community of Mexican bioinformatic software developers – the **[Community of Bioinformatic Software Developers](http://www.comunidadbioinfo.org/)** (_CDSB_, from its acronym in Spanish).

[![](http://www.comunidadbioinfo.org/wp-content/uploads/2018/03/Logo_texto.png)](http://www.comunidadbioinfo.org/r-bioconductor-developers-workshop-2018/)

The program of the workshop included talks, posters and lessons sessions as well as a two-day hands-on development hackathon. We had over 30 participants with strong quantitative background and experience in R programming from several LatAm countries.


<blockquote>

> 
> Excited about [#CDSBMexico](https://twitter.com/hashtag/CDSBMexico?src=hash&ref_src=twsrc%5Etfw)? It starts tomorrow!
> 
> 
¿Listos para mañana? 🇲🇽[https://t.co/UUhX5RMSut](https://t.co/UUhX5RMSut)

Schedule [https://t.co/BZTD7wGskI](https://t.co/BZTD7wGskI)

Materials [https://t.co/Oz2ingGije](https://t.co/Oz2ingGije)[#rstats](https://twitter.com/hashtag/rstats?src=hash&ref_src=twsrc%5Etfw) [#teaching](https://twitter.com/hashtag/teaching?src=hash&ref_src=twsrc%5Etfw) [@Bioconductor](https://twitter.com/Bioconductor?ref_src=twsrc%5Etfw) Thanks to [@lcgunam](https://twitter.com/lcgunam?ref_src=twsrc%5Etfw) [@ccg_unam](https://twitter.com/ccg_unam?ref_src=twsrc%5Etfw) [@LIIGH_UNAM](https://twitter.com/LIIGH_UNAM?ref_src=twsrc%5Etfw)
SoIBio [@RConsortium](https://twitter.com/RConsortium?ref_src=twsrc%5Etfw)[@WINTERGENOMICS](https://twitter.com/WINTERGENOMICS?ref_src=twsrc%5Etfw) [pic.twitter.com/YQxmnTNwQa](https://t.co/YQxmnTNwQa)

— ComunidadBioInfo (@CDSBMexico) [July 29, 2018](https://twitter.com/CDSBMexico/status/1023705341358469122?ref_src=twsrc%5Etfw)</blockquote>







### Community building


Unlike the US and Europe, where many universities have Computational Biology and Biostatistics Departments that gather experts in the field, in Mexico and Latin America experts in Biostatistics and Computational Biology are often spread across the country. The benefits of having Computational Biology and Biostatistics Departments are plenty: for example, experts can interact and work together on a specific problem, and researchers from other disciplines can easily find support and establish collaborations. The goal of CDSB is to create a virtual department where experts in Biostatistics and Computational Biology can discuss ideas and help each other across all stages of their careers.

The first event organized by CDSB, **LatAmBioc2018** included talks where both participants and speakers could start a dialogue and motivate each other by showcasing their work. As keynote invited speakers we had Daniel Piñero, who talked about population genetics of maize in Mexico; Alejandro Ponce-Mendoza, who showed elegant shiny apps to visualize ecological data along with maps; Teresa Ortiz, who talked about gender biases among R programmers; and Benilton Carvalho, who showed the development of personalized medicine in Brazil.


<blockquote>

> 
> We are having a great presentation from the founder of [@RLadiesCDMX](https://twitter.com/RLadiesCDMX?ref_src=twsrc%5Etfw), [@TeresaOM](https://twitter.com/TeresaOM?ref_src=twsrc%5Etfw), about getting rid of gender biases among the [#rstats](https://twitter.com/hashtag/rstats?src=hash&ref_src=twsrc%5Etfw) community. [#LatAmBioc18](https://twitter.com/hashtag/LatAmBioc18?src=hash&ref_src=twsrc%5Etfw) [@CDSBMexico](https://twitter.com/CDSBMexico?ref_src=twsrc%5Etfw) [#womeninSTEM](https://twitter.com/hashtag/womeninSTEM?src=hash&ref_src=twsrc%5Etfw) [pic.twitter.com/TPdDzHVdqC](https://t.co/TPdDzHVdqC)
> 
> 
— Alejandro Reyes (@areyesq) [August 2, 2018](https://twitter.com/areyesq/status/1025041063499771904?ref_src=twsrc%5Etfw)</blockquote>




The LatAmBioc2018 poster session was designed to encourage interdisciplinary collaborations. We invited people to contribute bioinformatic problems that would benefit from advice from experts such as the participants of LatAmBioc2018. We were happy to see that this event helped to create new collaborations.


<blockquote>

> 
> Here, we are presenting the basic structure and some examples with the framework -Winterflow- using [@nextflowio](https://twitter.com/nextflowio?ref_src=twsrc%5Etfw), [@Docker](https://twitter.com/Docker?ref_src=twsrc%5Etfw), [#mk](https://twitter.com/hashtag/mk?src=hash&ref_src=twsrc%5Etfw) and [#git](https://twitter.com/hashtag/git?src=hash&ref_src=twsrc%5Etfw) [pic.twitter.com/Ktn9o01X2Z](https://t.co/Ktn9o01X2Z)
> 
> 
— WINTER GENOMICS (@WINTERGENOMICS) [August 2, 2018](https://twitter.com/WINTERGENOMICS/status/1025149135081623553?ref_src=twsrc%5Etfw)</blockquote>










### A LatAm Bioconductor community


Anecdotally, some of us felt that Latin Americans were not fully represented in the Bioconductor Developers Meetings (see Leonardo Collado Torres’s **[blog post](http://lcolladotor.github.io/2018/04/19/latin-american-r-bioconductor-developers-workshop-2018)**). As scientists, we like our statements to be supported by data: the map below shows the affiliations, when available, of the contributors of the latest package submissions to the Bioconductor project. (These data were scraped using the Github API.) Although biases such as Mexican contributors with affiliations abroad might not have been considered, it is clear that only a few contributions come from Latin American countries.

![](http://www.comunidadbioinfo.org/wp-content/uploads/2018/09/mapa_editado-1024x444.png)










In hopes of filling this gap, we gathered a diverse team of instructors, including Martin Morgan, Benilton Carvalho and Selene Fernandez-Valverde, who taught participants how to develop R/Bioconductor packages. The main idea was to turn Bioconductor software users into Bioconductor software developers.


<blockquote>

> 
> Let's estimate Pi! Rcpp exercise! Rcpp sugar! Now I'm hungry, I want pie [@benilton](https://twitter.com/benilton?ref_src=twsrc%5Etfw) [@CDSBMexico](https://twitter.com/CDSBMexico?ref_src=twsrc%5Etfw) [#rstats](https://twitter.com/hashtag/rstats?src=hash&ref_src=twsrc%5Etfw) [#CDSBMexico](https://twitter.com/hashtag/CDSBMexico?src=hash&ref_src=twsrc%5Etfw) [#TIBMexico2018](https://twitter.com/hashtag/TIBMexico2018?src=hash&ref_src=twsrc%5Etfw) 🍰👩‍💻 [pic.twitter.com/2OeGWr35r3](https://t.co/2OeGWr35r3)
> 
> 
— Alejandra Medina-Rivera (@AleMedinaRivera) [August 1, 2018](https://twitter.com/AleMedinaRivera/status/1024705893148094464?ref_src=twsrc%5Etfw)</blockquote>




<blockquote>

> 
> How to debug R code with Martin Morgan :D [@CDSBMexico](https://twitter.com/CDSBMexico?ref_src=twsrc%5Etfw)
> 
> 
— Semiramis (@semiramis_cj) [August 1, 2018](https://twitter.com/semiramis_cj/status/1024716087185821696?ref_src=twsrc%5Etfw)</blockquote>




Participants attended lectures from Monday to Wednesday. Before the workshop, co-organizer Daniela Ledezma received and coordinated R package development proposals. On Wednesday afternoon, the participants formed teams and chose problems from Daniela’s curated list. They worked on their projects on Thursday and Friday, and we were very pleased with the final products: most teams wrote documented R packages that are available through GitHub. Two interesting examples are the prototype of the `regulonDB` package, which enables users to query RegulonDB within an R interphase, and `rGriffin`, an R interphase to inquire regulatory networks (for details, check **[their contributed blog post](http://www.comunidadbioinfo.org/r-gene-regulatory-interaction-formulator-for-inquiring-networks)**).


<blockquote>

> 
> Participants are gathering to work in collaborative projects targeting specific questions. The objetive is write a fully documented [#rstats](https://twitter.com/hashtag/rstats?src=hash&ref_src=twsrc%5Etfw) package by Friday. [@CDSBMexico](https://twitter.com/CDSBMexico?ref_src=twsrc%5Etfw) [#LatAmBioc18](https://twitter.com/hashtag/LatAmBioc18?src=hash&ref_src=twsrc%5Etfw) [pic.twitter.com/vDAvuOothC](https://t.co/vDAvuOothC)
> 
> 
— Alejandro Reyes (@areyesq) [August 1, 2018](https://twitter.com/areyesq/status/1024780770756440069?ref_src=twsrc%5Etfw)</blockquote>




<blockquote>

> 
> [#CDSBMexico](https://twitter.com/hashtag/CDSBMexico?src=hash&ref_src=twsrc%5Etfw) package developers course attendants presenting their projects [#TIBs2018](https://twitter.com/hashtag/TIBs2018?src=hash&ref_src=twsrc%5Etfw) [#rstats](https://twitter.com/hashtag/rstats?src=hash&ref_src=twsrc%5Etfw) [@CDSBMexico](https://twitter.com/CDSBMexico?ref_src=twsrc%5Etfw) [pic.twitter.com/ST44hCsLT6](https://t.co/ST44hCsLT6)
> 
> 
— Alejandra Medina-Rivera (@AleMedinaRivera) [August 3, 2018](https://twitter.com/AleMedinaRivera/status/1025429501478498304?ref_src=twsrc%5Etfw)</blockquote>


We are looking forward to seeing how the participants keep developing their R packages and collaborating through CSDB.









### Overachievers


We felt that the goals of the workshop were reached programmers from all over Latin America worked together and wrote new R packages, which hopefully will be submitted to Bioconductor soon.

We also had the chance to enjoy some good Mexican food and hang out with colleagues in less formal settings, such as lunches and group outings. To celebrate the conclusion of the workshop, we had an improvised party in a bar that played Latin American music. As any good party should, it ended up quite late. Some of us went to bed at 4am, but we woke up energized to keep CSDB going. Even now, two months on, we are excited to continue developing a strong community of bioinformatic developers in Latin America.


<blockquote>

> 
> In [#mexico](https://twitter.com/hashtag/mexico?src=hash&ref_src=twsrc%5Etfw), we don't only know how to do [#Science](https://twitter.com/hashtag/Science?src=hash&ref_src=twsrc%5Etfw) and good [#Bioinformatics](https://twitter.com/hashtag/Bioinformatics?src=hash&ref_src=twsrc%5Etfw) but also how to eat! Tacos during [#TIBMexico2018](https://twitter.com/hashtag/TIBMexico2018?src=hash&ref_src=twsrc%5Etfw) and [@qBio18](https://twitter.com/qBio18?ref_src=twsrc%5Etfw) @AlexielMedyna [@licloona1487](https://twitter.com/licloona1487?ref_src=twsrc%5Etfw) something great is happening here 😊 [pic.twitter.com/bC7ycfIA9n](https://t.co/bC7ycfIA9n)
> 
> 
— Ana Betty Villaseñor (@AnaBetty2304) [August 2, 2018](https://twitter.com/AnaBetty2304/status/1025115717279141889?ref_src=twsrc%5Etfw)</blockquote>










### Thank you


The LatAmBioc2018 would not have been possible without the time and support from the instructors, presenters, organizers and our sponsors CCG-UNAM, LCG-UNAM, LIIGH-UNAM, Winter Genomics, R Consortium and SoIBio.


