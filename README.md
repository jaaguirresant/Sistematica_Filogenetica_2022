# Sistematica Filogenetica 2022

# MÓDULO INFERENCIA FILOGENÉTICA

## Objetivos

1. Aprender las bases metodológicas de los principales métodos de inferencia filogenética a partir de matrices de caracteres homólogos y evaluar críticamente los supuestos, virtudes y desventajas de estos métodos.

2. Conocer los principios estadísticos para medición de la confianza de las hipótesis filogenéticas.  

3. Adquirir destrezas computacionales para llevar a cabo análisis de inferencia filogenética a partir de matrices de caracteres empíricas.

## Competencias

1. Habilidad de inferir e interpretar críticamente hipótesis de relaciones filogenéticas en cualquier grupo de organismos generadas bajo distintas metodologías a partir de matrices de caracteres.

2. Capacidad para interpretar fundamentos de la biología evolutiva en un árbol filogenético generado a partir de matrices de caracteres empíricas.

3. Entendimiento de la importancia de la inferencia filogenética para abordar problemas biológicos en un contexto evolutivo.

## Estructura general del módulo

### Preparación

Este módulo ha sido diseñado para estudiantes del curso de posgrado "Sistemática Filogenética y Nomenclatura Botánica/Zoológica" del programa de Maestría en Ciencias-Biología de la Universidad Nacional de Colombia. Los estudiantes inscritos en este curso ya debieron haber tomado cinco semanas de temas introductorios sobre evolución y sistemática filogenética para poder seguir con los contenidos de este módulo.

#### Los requerimientos y materiales básicos para llevar a cabo este módulo son los siguientes:

Computador o laptop con los siguientes programas instalados: 
- Editor de texto (recomendados notepad++ para Windows y Atom para Mac).
- [Mesquite](https://www.mesquiteproject.org/). Útil para construir y/o visualizar matrices de caracteres.
- R y R Studio (bajar los paquetes: Ape, Claddis, Phangorn, Phytools).
- [TNT](http://www.lillo.org.ar/phylogeny/tnt/). GUI solo para Windows. Para análisis de Máxima Parsimonia.
- [jmodelTest](https://github.com/ddarriba/jmodeltest2). Para selección de modelos evolutivos de secuencias de nucleótidos.
- [RAxML-GUI](https://antonellilab.github.io/raxmlGUI/). Para análisis de Máxima Verosimilitud.
- [IQTree](http://www.iqtree.org/). Para análisis de Máxima Verosimilitud.
- [MrBayes](http://nbisweden.github.io/MrBayes/download.html). Para análisis de Inferencia Bayesiana.
- [BEAST 2](https://www.beast2.org/). Para análisis de Inferencia Bayesiana y tiempos de divergencia.
- [ASTRAL](https://github.com/smirarab/ASTRAL/blob/master/README.md). Para inferencia de árboles de especies a partir de árboles de genes.
- [FigTree](https://github.com/rambaut/figtree/releases). Para visualización y edición de árboles filogenéticos.
- [Tracer](https://github.com/beast-dev/tracer/releases/tag/v1.7.1). Para visualizar resultados de MCMC.

**Nota:** Es posible que usemos otros programas, pero les avisaré con tiempo. Todos los programas de inferencia filogenética vienen acompañados con sus respectivos tutoriales. Se sugiere seguirlos en su tiempo libre; no se limiten únicamente a los ejercicios de la clase.  

## Contenido

**Clase 1.** Se hará un breve repaso de los recursos informáticos para construcción de matrices con editor de texto, el programa Mesquite y R. Para esta parte se deben descargar las siguientes matrices para este ejercicio: [ADN.tnt](/Clase_1/ADN.tnt), [morfologia.tnt](/Clase_1/morfologia.tnt),[morfologia.nex](/Clase_1/morfologia.nex), [ADN.nex](/Clase_1/ADN.nex), [ADN.phy](/Clase_1/ADN.phy), [ADN_1.nex](/Clase_1/ADN_1.nex), [ADN_2.nex](/Clase_1/ADN_2.nex). 

**[Ir al taller aquí](/Clase_1/Taller_matrices.md)**

En la segunda parte de la clase, se hará un breve repaso de R a través de un ejercicio de visualización y manipulación de archivos de árboles filogenéticos. Para esta parte de la clase haremos un ejercicio práctico en R para visualizar y manipular árboles filogenéticos 

**[Ir al taller aquí](/Clase_1/Taller_arboles.md)**
**[Tambipen puede bajar el script en R directamente aquí](/Clase_1/Manipulacion_arboles.R)**

**_NOTA:_** Leer los siguientes artículos para la clase del miércoles:

- Argumentación Hennigiana y Máxima Parsimonia: [Wiley & Lieberman 2011 - Capítulo 6](/Clase_1/MP_Wiley_Lieberman.pdf)

- [González 1999](/Clase_1/Gonzalez_1999_Aristolochia.pdf)
