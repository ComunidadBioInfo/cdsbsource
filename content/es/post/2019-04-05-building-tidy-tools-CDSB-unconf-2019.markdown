---
authors: ["admin"]
date: 2019-04-05 13:30:00+00:00
slug: building-tidy-tools-CDSB-runconf-2019
title: "Taller CDSB 2019: Cómo Crear y Ordenar Herramientas 'Tidy'"
categories: ["Events", "rstats", "rstatsES"]
featured: true
---

#### Comunidad de Desarrolladores de Software en Bioinformática

 	
  * Página del taller: [https://comunidadbioinfo.github.io/es/post/building-tidy-tools-CDSB-runconf-2019/](https://comunidadbioinfo.github.io/es/post/building-tidy-tools-CDSB-runconf-2019/)

 	
  * Nivel: **intermedio - avanzado**

 	
  * Languaje: **español**^[If you speak English but not Spanish please let us know so we can plan accordingly.]

 	
  * Cuando: Julio 29 - Augusto 2, 2018

 	
  * Donde: Auditorio del [Centro de Ciencias Genómicas](http://www.ccg.unam.mx), Cuernavaca, Mexico

 	
  * Twitter: [#CDSBMexico](https://twitter.com/search?f=tweets&q=%23CDSBMexico)

 	
  * Facebook: [@CDSBMexico](https://www.facebook.com/CDSBMexico/)

 	
  * GitHub: [https://github.com/ComunidadBioInfo/tidy-tools-CDSB-runconf-2019](https://github.com/ComunidadBioInfo/tidy-tools-CDSB-runconf-2019)

 	
  * [Registro](http://congresos.nnb.unam.mx/TIB2019)  

 	
  
## Pre-requisitos


Requisitos de conocimientos previos

 	
  * Los participantes deberán tener conocimientos básicos del lenguaje de programación R: asignación de variables, lectura de archivos: read.csv, read.delim, read.table; estructuras de datos: matrix, dataframe, list; tipos de datos: character, numeric, factor, logical, etc; instalación y uso de paquetes.
  * Saber instalar paquetes de R.
  * Saber usar RStudio.

Requisitos técnicos

 	
  * Computadora Personal. Un mínimo de 8 GB de RAM, un ratón y espacio de disco suficiente para archivos de texto y archivos de imagen. Privilegios de administrador para instalar y ejecutar utilidades de RStudio.



## Introducción

En años recientes, [R](https://cran.r-project.org/) se ha convertido en uno de los lenguajes de programación más usados para la ciencia de datos. La explosión en la disponibilidad de datos en muchos campos ha incrementado la demanda para personas capacitadas en el analísis de estos datos, tal como es el caso en la Bioinformática. Los usarios de `R` empiezan usando herramientas que otros han compartido con la comunidad internacional de forma libre. Mientras van analizando más conjuntos de datos, estos usuarios adquieren más habilidades con `R`. Durante este proceso incluso es posible que empiecen a interactuar con desarrolladores de `R` vía páginas web como [RStudio Community](https://community.rstudio.com/), [Bioconductor Support](https://support.bioconductor.org/) or vía Twitter usando la equiqueta [#rstats](https://twitter.com/search?q=%23rstats) o [#rstatsES](https://twitter.com/search?q=%23rstatsES). Eventualmente algunos de los usuarios de `R` van a querer escribir sus propias funciones y compartirlas en línea con otras personas. Pueden lograr este objetivo si crean paquetes de `R` y los comparten vía repositorios como [CRAN](https://cran.r-project.org/) y [Bioconductor](http://bioconductor.org/) o simplemente vía [GitHub](https://github.com). En este taller los participantes completaran el taller _Building Tidy Tools_ que fue originalemnte impartido durante [rstudio::conf 2019](https://blog.rstudio.com/2019/02/06/rstudio-conf-2019-workshops/) y luego construirán sus propios paquetes de `R` colaborando con otros participantes, siguiendo una dinámica similar a la del [rOpenSci unconf18](http://unconf18.ropensci.org/).


Este taller está enfocado hacia alumnos e investigadores interesados en análisis de datos. Queremos promover solicitudes de expertos en diversas disciplinas, incluyendo mas no limitandonos a biológos, bioinformáticos, científicos de datos, ingenieros de software, programadores y usuarios de R en general. Los principales objetivos del taller son:

1. Enseñarle a los participantes los principios de la ciencia de datos vía el desarrollo de paquetes de R/Bioconductor.

2. Transformar usuarios de software (de bioinformática) en desarrolladores de software (de bioinformática).

3. Fomentar el intercambio de conocimiento y establecer colaboraciones multidisciplinarias.

4. Crear una comunidad de científicos Latino Americanos comprometidos con el desarrollo de software para análisis de datos (biológicos).

5. Entrenar a instructores (en bioinformática) para que puedan fomentar el crecimiendo de sus comunidades locales.


Este taller es parte de un proyecto a largo plazo para crear una comunidad Latino Americana de desarrolladores de software. Esperamos poder organizar talleres en el futuro de forma sistemática (similar a BioC, EuroBioC y BioCAsia) donde los participantes presenten sus contribuciones de software. Queremos proveer un ambiente amigable para todos así que les pedimos que sigan el [código de conducta](../../codigo-de-conducta/).


## Programa


| **Day 1: Julio 29, 2018**  |      |      |
| ------------------ | ---------------------------------- | ----------------------------- |
| | Inaguración  |  |
| | Bienvenida a la CDSB: la historia de nuestra comunidad y hacia donde vamos | [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/)    |
| | Paquetes | [Alejandro Reyes](http://comunidadbioinfo.github.io/authors/areyes/) and [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) |
| | Pruebas | [Alejandro Reyes](http://comunidadbioinfo.github.io/authors/areyes/) and [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) |
| | Diseño de API | [Alejandro Reyes](http://comunidadbioinfo.github.io/authors/areyes/) and [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) |
| **Day 2: Julio 30, 2019** |      |      |
| | Programación Funcional | [Alejandro Reyes](http://comunidadbioinfo.github.io/authors/areyes/) and [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) |
| | Erroress | [Alejandro Reyes](http://comunidadbioinfo.github.io/authors/areyes/) and [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) |
| | Programación Orientada a Objetos | [Alejandro Reyes](http://comunidadbioinfo.github.io/authors/areyes/) and [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) |
|  | (por definir) Sesión de pósters |      |
| **Day 3: Julio 31, 2019** |      |      |
| | Evaluación "Tidy" | [Alejandro Reyes](http://comunidadbioinfo.github.io/authors/areyes/) and [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) |
| | Documentar y Compartir | [Alejandro Reyes](http://comunidadbioinfo.github.io/authors/areyes/) and [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) |
| | Introducción a GitHub | [Alejandra Medina-Rivera](http://comunidadbioinfo.github.io/authors/amedina/) |
| **Day 4: Augusto 1, 2019** |      |      |
| | Introducción a `runconf` | [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) |
| | Actividades para construir la comunidad | |
| | Votación y selección de proyectos | |
|  | Trabajar en desarrollar un paquete de R de forma colaborativa | [Alejandra Medina-Rivera](http://comunidadbioinfo.github.io/authors/amedina/), [Alejandro Reyes](http://comunidadbioinfo.github.io/authors/areyes/) and [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) |
| **Day 5: Augusto 2, 2019** |      |      |
|  | Trabajar en desarrollar un paquete de R de forma colaborativa | [Alejandra Medina-Rivera](http://comunidadbioinfo.github.io/authors/amedina/), [Alejandro Reyes](http://comunidadbioinfo.github.io/authors/areyes/) and [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) |
|  | Presentación de proyectos del `runconf` |      |
|  | Clausura y recordatorio de oportunidades para participar en la CDSB |      |


### Construir Herramientas Ordenadas

Charlotte Wickham y Hadley Wickham fueron los instructores de la versión [original de este taller](https://github.com/rstudio/rstudio-conf/blob/master/2019/workshops.md#building-tidy-tools) en rstudio::conf 2019. Aceptaron amablemente compartir con nosotros los archivos fuente que traducieremos al español para este taller. Si quieres leer la versión original en inglés de este texto, checa [nuestro anuncio del taller en inglés](https://comunidadbioinfo.github.io/post/building-tidy-tools-CDSB-runconf-2019/).

> Este es un taller de dos días para quienes sean usuarios del tidyverse y que ahora quieren expander sus necesidades. Hablaremos sobre diseño de APIs, herramientas para programación funcional, las bases del diseño de objetos en S3, y el system de evaluación ordenada (tidy eval) para evaluación no estándar (NSE en inglés).
>
> Aprendás formas eficientes de escribir funciones de R de alta calidad, usando una serie de convenciones codificadas en un paquete. También aprenderás como diseñar pruebas unitarias para tu software, que te permiten garantizar que tus funciones hacen lo que fueron diseñadas para hacer. Domina el arte de escribir funciones que hacen una sola cosa bien y que pueden ser combinandas de forma fluida para resolver problemas complejos. Repasaremos errores comunes al escribir funciones y como evitarlos.
>
> Aprende a escribir colecciones de funciones que funcionan bien de forma conjunta, y sigue limeamientos existentes para que usuarios nuevos sientan que son fáciles de aprender.
>
> Deberías tomar este taller si tienes experiencia programando en R y quieres aprender a resolver problemas de gran escala. Le sacarás más jugo al taller si ya estás familiarizado con funciones de R y te sientes cómodo con las estructuras básicas de R (vectores, matrices, arreglos, listas y tablas).

En vez de enseñar el taller en dos días, lo haremos en dos días y medio para que tengan más tiempo para digerir todo el material y para que tengamos tiempo de enseñar que es Git y GitHub.


### CDSB `runconf`

Los eventos de `R` "unconference" (runconf) típicamente involucran dos etapas con una tercera opcional. Primero los participantes crean "issues" semanas antes del runconf donde comparten ideas sobre las cuales potencialmente podrían trabajar durante los dos días del runconf. En la segunda etapa, los participantes se conocen entre todos a través de dinámicas diseñadas para romper el hielo. Luego trabajan de forma colaborativa durante dos días en los proyectos que hayan recibido votos. Es aquí cuando los participantes aprenden de las habilidades de cada quien y donde pueden vivir la experiencia de desarrollar software de acceso libre de forma colaborativa. Al final, todos comparten su experiencia con el resto del grupo. En la tercera y última etapa, los participantes del runconf puede que continuen a interactuar entre ellos para pulir los paquetes de `R` en los cuales hayan trabajado durante runconf, iniciar nuevas colaboraciones y/o escribir entradas en el blog sobre su experiencia.

Hay muchas entradas de blog sobre eventos de rOpenSci unconf. Un runconf reciente fue `chirunconf` del cual pueden leer más en el blog de [Sharla Gelfand](https://sharla.party/posts/chirunconf/).

Si van a participar en nuestro taller, les vamos a pedir que propongan al menos una idea para un paquete de R vía la creación de un "GitHub Issue" en nuestro [ repositorio de GitHub para el taller](https://github.com/ComunidadBioInfo/tidy-tools-CDSB-runconf-2019/issues). Si necesitan algo de inspiración, revisen las ideas que otros propusieron para [rOpenSci unconf18](https://github.com/ropensci/unconf18/issues). También les pediremos que todos se familiarizen con las propuestas de los demás antes del inicio del taller.


## Instructores:


- [Alejandra Medina-Rivera](http://comunidadbioinfo.github.io/authors/amedina/) (International Laboratory for Human Genome Research, Juriquilla, Mexico)
  
- [Alejandro Reyes](http://comunidadbioinfo.github.io/authors/areyes/) (Dana-Farber Cancer Institute, Boston, USA)

- [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) (Lieber Institute for Brain Development, Baltimore, USA). Leonardo tómo el taller original de _Building Tidy Tools_ en [rstudio::conf 2019](https://blog.rstudio.com/2019/02/06/rstudio-conf-2019-workshops/) gracias a una beca de diversidad. También atendió el [rOpenSci unconf 2018](http://unconf18.ropensci.org/).


## Comité Organizador:

- [Alejandra Medina-Rivera](http://comunidadbioinfo.github.io/authors/amedina/) (International Laboratory for Human Genome Research, Juriquilla, Mexico)
  
- [Alejandro Reyes](http://comunidadbioinfo.github.io/authors/areyes/) (Dana-Farber Cancer Institute, Boston, USA)

- [Delfino García](http://comunidadbioinfo.github.io/authors/delfinog/) (Center for Genomic Sciences, Cuernavaca, Mexico)

- [Heladia Salgado](http://comunidadbioinfo.github.io/authors/hsalgado/) (Center for Genomic Sciences, Cuernavaca, Mexico)

- [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) (Lieber Institute for Brain Development, Baltimore, USA)


## [Código de Conducta](../../codigo-de-conducta/)



## Patrocinadores


[Sé nuestro **patrocinador**](../../niveles-de-patrocinio/)

| | | |
| --- | --- | --- |
| [![Centro de Ciencias Genómicas UNAM](/img/CCG_Logo_HR-300x114.png)](http://www.ccg.unam.mx) | [![](/img/LCG_Logo_HR-white.png)](http://www.lcg.unam.mx) | [![](/img/logo-liigh-unam.png)](http://liigh.unam.mx/) |




