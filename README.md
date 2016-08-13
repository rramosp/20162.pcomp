# **Computación Paralela** 2016 - Semestre II

## Maestría en Ingeniería Computacional - Universidad de Caldas

Raúl Ramos-Pollán, Universidad Industrial de Santander, \[[+info](https://sites.google.com/site/rulixrp/courses)\] [rramosp@uis.edu.co](mailto:rramosp@uis.edu.co)

---

**Estaremos usando:**

+ una máquina virtual configurada para las lecciones 1, 2 y 3, con CentOS 6, OpenMP y Python Anaconda para que puedas realizar de manera independiente tus ejercicios (_contáctame para obtenerla_)
+ una máquina virtual con la instalación del [Spark](http://spark.apache.org/) para la lección 4. Seguiremos parte del contenido del curso en EDX sobre [Scalable Machine Learning](https://courses.edx.org/courses/BerkeleyX/CS190.1x/1T2015/info)
+ la infraestructura `guane` de [Centro de Supercómputo y Cálculo Científico de la UIS](http://www.sc3.uis.edu.co) sobre todo para las pruebas de escalabilidad y uso de CUDA/GPUs (_instrucciones de acceso más abajo_)

**Crea una copia local de este repositorio para trabajar en los ejercicios desde la máquina virtual del curso y lanza tu servidor personal del entorno de ejecución de `ipython notebooks`**

    :::console
    git clone https://bitbucket.org/rramosp/ucaldas.20152.msc
    ipython notebook

## Lección 1 - Introducción

**Temas:** Uso infraestructura SC3-UIS, Paralelismo y computación, Computación distribuida, Arquitecturas de procesadores

**Refs:** Supercomputación y Cálculo Científico UIS [[web site](http://www.sc3.uis.edu.co/)], Caché effects [[enlace](http://igoro.com/archive/gallery-of-processor-cache-effects/)] , HPC Course @UWisc [[enlace](http://sbel.wisc.edu/Courses/ME964/2012/)]

## Lección 2 - OpenMP
**Temas:** Modelo de programación, Variables compartidas y sincronización, Tareas, Optimización

**Refs:** Tim Mattson, Intel [[video lectures](http://www.youtube.com/watch?v=nE-xN4Bf8XI&list=PLLX-Q6B8xqZ8n8bwjGdzBJ25X2utwnoEG), [materials](https://software.intel.com/en-us/courseware/249662)], Lista de recursos [[enlace](http://www.compunity.org/training/tutorials/)]

## Lección 3 IPython Parallel
**Temas:** Modelo de programación, Distribución de Tareas, Comunicaciones, Coordinación, Sincronización, Procesamiento de imágenes.

**Refs:** [IPython for Parllel Computing](https://ipython.org/ipython-doc/3/parallel/index.html)

## Lección 4 Paralelismo Masivo con Apache Spark
**Temas:** Modelos de paralelismo en Big Data, Resilient Distributed Datasets, Modelo de programación, Acciones y Operaciones Spark

**Refs:**  Seguiremos parte del curso sobre [Scalable Machine Learning](https://courses.edx.org/courses/BerkeleyX/CS190.1x/1T2015/info) en EDX. Los siguientes ProblemSets son parte de los assignments de dicho curso.


## Uso infraestructura **GUANE** @ **UIS**

La puerta de entrada a **GUANE** a través de los notebooks de IPython es

[www.sc3.uis.edu.co/guaneJ10](www.sc3.uis.edu.co/guaneJ10)

donde el `J10` puede cambiar en función de la asignación de recursos al curso.

Si es la primera vez que entras, crea una copia del repositorio de ejercicios para poder trabajarlos de manera independiente 

    :::console
    wget https://github.com/rramosp/20162.pcomp/archive/master.zip
    unzip master
