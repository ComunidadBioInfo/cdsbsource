---
authors: ["admin"]
date: 2020-03-05 13:30:00+00:00
slug: cdsb2020-building-workflows-with-rstudio-and-scrnaseq-with-bioconductor
title: "Taller CDSB 2020: Construyendo flujos de trabajo con RStudio y Bioconductor para datos transcriptómicos de célula única (scRNA-seq)"
categories: ["Events", "rstats"]
featured: false
---

_Este taller es parte del [Encuentro de Bioinformática en México (EBM) 2020](http://www.nnb.unam.mx/TIB2020/) organizado por la CDSB junto con:_

| TIB2020 | RMB | NNB | CCG-UNAM |
| --- | --- | --- | --- |
| [<img src="http://www.nnb.unam.mx/TIB2020/wp-content/uploads/sites/2/2020/03/TIF-Logo_2020.png" width="150px" />](http://www.nnb.unam.mx/TIB2020/) | [<img src="http://www.nnb.unam.mx/TIB2020/wp-content/uploads/sites/2/2020/03/RMB_Logo-horizontal.png" width="150px" />](https://www.redmexicanadebioinformatica.org/) | [<img src="http://www.nnb.unam.mx/TIB2020/wp-content/uploads/sites/2/2020/03/logo-principal.png" width="150px" />](http://www.nnb.unam.mx/) | [<img src="http://www.nnb.unam.mx/TIB2020/wp-content/uploads/sites/2/2020/03/CCG_Logo_HR.png" width="150px" />](http://www.ccg.unam.mx/) |

#### Comunidad de Desarrolladores de Software en Bioinformática  (CDSB)

 	
  * [Página del taller](https://comunidadbioinfo.github.io/es/post/cdsb2020-building-workflows-with-rstudio-and-scrnaseq-with-bioconductor/)

 	
  * Nivel: **intermedio - avanzado**

 	
  * Languaje: **español**

 	
  * Cuando: Agosto 3 - Agosto 7, 2020 (9 am a 5:30 pm excepto el viernes que será hasta las 2:30 pm)

 	
  * Donde: en línea. El horario está en hora del centro de México.

 	
  * Twitter: [@CDSBMexico](https://www.twitter.com/CDSBMexico/)

 	
  * Facebook: [@CDSBMexico](https://www.facebook.com/CDSBMexico/)

 	
  * GitHub: [https://github.com/ComunidadBioInfo/cdsb2020](https://github.com/ComunidadBioInfo/cdsb2020)

 	
  * [Registro](http://www.nnb.unam.mx/TIB2020/)




## **Resumen**

¡Únete a nuestro taller del 2020! Este año te enseñaremos cómo mejorar tus habilidades para interactuar con el lenguaje de programación R con diversas estrategias para organizar tu código y tus proyectos. Esto te permitirá hacer análisis documentados que sean fácilmente reproducibles y puedas compartir con otros colaboradores (de la academia a la industria). Como caso de estudio, aprenderemos las herramientas estadísticas para analizar datos de transcriptómica en células únicas usando Bioconductor. El completar este taller te ayudará en tus diversos proyectos de R y de análisis de datos biológicos: todos tus análisis saldrán beneficiados, las ideas detrás de single-cell RNA-seq se usan en muchos otros análisis bioinformáticos.

<iframe src="https://giphy.com/embed/L40sNfcoJs5Op5afQU" width="480" height="240" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/hustlersmovie-hustlers-movie-hustler-L40sNfcoJs5Op5afQU">via GIPHY</a></p>

## **Pre-requisitos**


**Requisitos de conocimientos previos**

 	
  * Los participantes deberán tener conocimientos básicos del lenguaje de programación R: asignación de variables, lectura de archivos: `read.csv`; estructuras de datos: `matrix`, `data.frame`, `list`; tipos de datos: `character`, `numeric`, `factor`, `logical`, etc; instalación y uso de paquetes.
  * Saber instalar paquetes de R.
  *	Saber usar RStudio.
  *	Interés en hablar sobre problemas de generación de código.
  *	Interés en aprender buenas prácticas para organizar tu trabajo y comenzar a compartir tu código con otras personas. 
  *	Deseas mantenerte conectado con la comunidad de desarrolladores de R. 
  *	Deseas aprender cómo analizar datos usando paquetes de R/Bioconductor.
  

**Requisitos técnicos**

 	
  * Computadora Personal. Un mínimo de 8 GB de RAM, un ratón y espacio de disco suficiente para archivos de texto y archivos de imagen. Privilegios de administrador para instalar y ejecutar utilidades de RStudio.
  



## **Introducción**

En años recientes, [R](https://cran.r-project.org/) se ha convertido en uno de los lenguajes de programación más usados para la ciencia de datos. La explosión en la disponibilidad de datos en muchos campos ha incrementado la demanda para personas capacitadas en el analísis de estos datos, tal como es el caso en la Bioinformática. Los usarios de `R` empiezan usando herramientas que otros han compartido con la comunidad internacional de forma libre. Mientras van analizando más conjuntos de datos, estos usuarios adquieren más habilidades con `R`. Durante este proceso incluso es posible que empiecen a interactuar con desarrolladores de `R` vía páginas web como [RStudio Community](https://community.rstudio.com/), [Bioconductor Support](https://support.bioconductor.org/) or vía Twitter usando la etiqueta [#rstats](https://twitter.com/search?q=%23rstats) o [#rstatsES](https://twitter.com/search?q=%23rstatsES). Eventualmente algunos de los usuarios de R van a querer escribir sus propias funciones y organizar su código en diversos proyectos. Es en ese punto que es útil aprender cómo organizar tu código para que tu vida como programador de R sea más sencilla, de tal manera que le dediques más tiempo a tus proyectos en vez de a recordar dónde está tu código o qué hiciste hace unas semanas. Para poner estos temas en práctica, revisaremos los métodos más recientes para analizar datos de single cell RNA-seq (transcriptómica en células únicas) usando paquetes de R especializados para este objetivo que están disponibles libremente vía [Bioconductor](https://bioconductor.org). 


Los instructores de este taller han participado en la CDSB desde su fundación y han ido a cursos como [BioC2019](http://bioc2019.bioconductor.org/), [rstudio::conf(2020)](https://resources.rstudio.com/rstudio-conf-2020), entre otros. En años anteriores enseñamos cómo hacer paquetes de R y Bioconductor, que son de gran utilidad para compartir código con otras personas. Recientemente alumnos de la CDSB enviaron su [primer paquete de R a Bioconductor](https://comunidadbioinfo.github.io/es/post/from-bioconductor-users-to-developers-our-first-community-submission/), lo cual representa un aumento porcentual enorme en la representación de latinoamericanos en la comunidad de desarrolladores de Bioconductor, lo cual demuestra que participar en la CDSB tiene un impacto más allá de la semana del taller. Para 2020 tendremos un enfoque práctico y a la vez manteniendo objetivos de la CDSB que son:


1. Transformar usuarios de software (de bioinformática) en desarrolladores de software (de bioinformática).

2. Fomentar el intercambio de conocimiento y establecer colaboraciones multidisciplinarias.

3. Crear una comunidad de científicos Latino Americanos comprometidos con el desarrollo de software para análisis de datos (biológicos).

4. Entrenar a instructores (en bioinformática) para que puedan fomentar el crecimiendo de sus comunidades locales.


La porción del taller sobre scRNA-seq estará basada en el libro [_Orchestrating Single Cell Analysis with Bioconductor_](https://osca.bioconductor.org/) que fue publicado en _Nature Methods_ ([DOI](https://doi.org/10.1038/s41592-019-0654-x)) y que es de los [artículos con mayor publicidad](https://www.altmetric.com/details/71569824) en 2020.



Este taller es parte de un proyecto a largo plazo para crear una comunidad Latino Americana de desarrolladores de software. Esperamos poder organizar talleres en el futuro de forma sistemática (similar a BioC, EuroBioC y BioCAsia) donde los participantes presenten sus contribuciones de software. Queremos proveer un ambiente amigable para todos así que les pedimos que sigan el [código de conducta](../../codigo-de-conducta/).




## **Programa**

De 9 am a 5:30 pm en el horario central de Mexico (el viernes terminaremos a las 2:30 pm) con tiempo para descansar y comer. El horario detallado y las ligas de Zoom serán compartidos con los participantes registrados a través del calendario privado de Google de la CDSB. Para ver más detalles del horario favor de revisar [el repositorio CDSB2020 del taller](https://github.com/ComunidadBioInfo/cdsb2020).


De 8 a 9 am todos los días tendremos sesiones de ayuda de instalación de software para quien necesite la ayuda.


Día 1

* Inauguración EBM2020
* Bienvenida a la CDSB
* Introducciones de los participantes
* Flujo de trabajo orientado a proyectos:
  - Introducción al flujo de trabajo orientado a proyectos.
  - Trabajando con proyectos versus scripts.
  - Generación de un proyecto.
  - Paths seguros.
  - ¿Qué nombre le doy a mi archivo?

Día 2

* Uso de Git y GitHub.
* Modificando los archivos de inicio de R.
* Escritura y documentación de funciones.
* Debugging.

Día 3

* Buenas prácticas de configuración y mantenimiento de espacios de trabajo.
* Foto / video remoto.
* Instalación de paqueterías desde código fuente.
* Visión general del procesamiento de datos de scRNA-seq
* Actividades para construir la comunidad
* Presentación del material para scRNA-seq

Días 4 

* Introducción a scRNA-seq
* Introducción a scRNA-seq con Bioconductor
* Estructura e importe de datos
* Control de calidad
* Normalización de datos

Día 5

* Selección de genes
* Reducción de dimensiones
* Clustering y detección de genes diferencialmente expresados
* spatialLIBD: análisis de datos de la plataforma Visium de 10x Genomics
* Evaluación del taller
* Clausura y recordatorio de la CDSB


## **Instructores**

- [Alejandra Medina-Rivera](http://comunidadbioinfo.github.io/authors/amedina/) (International Laboratory for Human Genome Research, Juriquilla, Querétaro, Mexico) Alejandra recientemente dio una [plática plenaria en el evento de Mujeres en Ciencias de Datos (Women in Data Science)](https://twitter.com/MxPyladies/status/1233208231184543745?s=20) de la Ciudad de México.

- [Alejandro Reyes](http://comunidadbioinfo.github.io/authors/areyes/) (Data Scientist, Novartis, Basel, Switzerland). Alejandro recientemente trabajó en el proyecto de [regutools](http://bioconductor.org/packages/regutools) con miembros de la CDSB que fue publicado en [Oxford Bioinformatics](https://academic.oup.com/bioinformatics/article-abstract/doi/10.1093/bioinformatics/btaa575/5861528?redirectedFrom=fulltext).

- [Joselyn Chávez](http://comunidadbioinfo.github.io/authors/josschavezf) (IBT-UNAM, Cuernavaca, Morelos, Mexico). Joselyn presentó su trabajo en [BioC2019](http://bioc2019.bioconductor.org/) gracias a una beca, fue a [rstudio::conf(2020)](https://resources.rstudio.com/rstudio-conf-2020) gracias a una beca de diversidad donde tomó el taller de _What They Forgot to Teach You about R_ workshop, y recientemente fue parte del equipo que [envió el primer paquete de `R` a Bioconductor por parte de ex-alumnos de la CDSB](https://comunidadbioinfo.github.io/post/from-bioconductor-users-to-developers-our-first-community-submission/). Initialmente fue una alumna en CDSB2018.

- [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) (Lieber Institute for Brain Development, Baltimore, MD, USA). Leonardo recentiemente publicó un [artículo (pre-print)](https://twitter.com/lcolladotor/status/1233661576433061888?s=20) sobre la transcriptómica _espacial_ usando la tecnología Visium de 10x Genomics.

- [Marcel Ramos Perez](http://comunidadbioinfo.github.io/authors/mramos/) (Roswell Park Comprehensive Cancer Center and CUNY School of Public Health, USA). Marcel es parte del [Bioconductor Core Team](http://bioconductor.org/about/core-team/) y autor de muchos paquetes de Bioconductor incluyendo a [MultiAssayExperiment](http://bioconductor.org/packages/MultiAssayExperiment).

- [Maria Teresa Ortiz](http://comunidadbioinfo.github.io/authors/mteresa/) (CONABIO and ITAM, Mexico). Teresa presentó en [rstudio::conf(2020)](https://resources.rstudio.com/rstudio-conf-2020) su trabajo sobre algoritmos de conteo rápido para las elecciones presidenciales de México.

## **Comité Organizador**

- [Alejandra Medina-Rivera](http://comunidadbioinfo.github.io/authors/amedina/) (International Laboratory for Human Genome Research, Juriquilla, Querétaro, Mexico)
  
- [Alejandro Reyes](http://comunidadbioinfo.github.io/authors/areyes/) (Data Scientist, Novartis, Basel, Switzerland)

- [Joselyn Chávez](http://comunidadbioinfo.github.io/authors/josschavezf) (IBT-UNAM, Cuernavaca, Morelos, Mexico)

- [Leonardo Collado-Torres](http://comunidadbioinfo.github.io/authors/lcollado/) (Lieber Institute for Brain Development, Baltimore, MD, USA)


## **[Code of Conduct](../../codigo-de-conducta/)**



## **Patrocinadores**

[Sé nuestro **patrocinador**](../../niveles-de-patrocinio/)

### Nivel platino

### Nivel oro

### Nivel plata

[<img src="http://bioconductor.org/images/logo/jpg/bioconductor_logo_cmyk.jpg" width="250px">](http://bioconductor.org/)

[<img src="/img/RConsortium_Horizontal_Pantone-768x173.png" width="250px">](https://www.r-consortium.org/)

## Organizadores

CDSB es un nodo de la [Red Mexicana de Bioinformática](https://www.redmexicanadebioinformatica.org/) y organiza el taller anual junto con el [Nodo Nacional de Bioinformática (NNB)](http://www.nnb.unam.mx/).

[<img src="http://www.nnb.unam.mx/TIB2020/wp-content/uploads/sites/2/2020/03/TIF-Logo_2020.png" width="250px" />](http://www.nnb.unam.mx/TIB2020/)

[<img src="http://www.nnb.unam.mx/TIB2020/wp-content/uploads/sites/2/2020/03/RMB_Logo-horizontal.png" width="250px" />](https://www.redmexicanadebioinformatica.org/)

[<img src="http://www.nnb.unam.mx/TIB2020/wp-content/uploads/sites/2/2020/03/logo-principal.png" width="250px" />](http://www.nnb.unam.mx/)


[<img src="http://www.nnb.unam.mx/TIB2020/wp-content/uploads/sites/2/2020/03/CCG_Logo_HR.png" width="250px" />](http://www.ccg.unam.mx/)

Con apoyo de:

[<img src="http://www.nnb.unam.mx/TIB2020/wp-content/uploads/sites/2/2020/03/LCG_Logo_HR-white-e1522778427811.png" width="250px" />](https://www.lcg.unam.mx/)

[<img src="https://www.zaragoza.unam.mx/portal/wp-content/Portal2015/Descargas/logo_unam_azul.jpg" width="250px">](http://www.unam.mx/)



