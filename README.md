### ARCHIVO EN CONSTRUCCIÓN

# Proyecto_Final-Bioinf2017-II
Por Madisson Azucena Luna Bárcenas 
__________

Este repositorio contiene datos tomados RADseq pre-procesados y mapeados en formato .bam de *Dipodomys merriami* y *D. deserti*, tomados de Jezckova et al. 2015<sup>1 2</sup> disponibles en Dryad ("Jezkova_2014_Dipodomys_Mapped_Reads.tar.bz2") y un análisis de Genética de poblacionesde los mismos

En la carpeta **bin** se encuentran los scripts para:
 
1.	Realizar el llamado de los SNP´s y obtener estadísticos de diversidad Pi, FST y heterocigocidad con pipelines de Stacks ver.1.46; **Script_Stacks**
2.	Hacer análisis comparativos de los estadísticos de genética de poblaciones entre especies y entre poblaciones con R ver. 3.3.0; **Script_RGenPob**
3.	Hacer un PCA con SNPRelate para separar poblaciones; **Script_SNPRelate** 
4.	hacer análisis de estructura con FastStructure **Script_FStr**
 
En la carpeta **data** se encuentra:

*	Una submuestra de los datos .bam que se analizaron con la pipeline de Stacks (**Nota:** Estos datos son solo una parte de los datos que se utilizaron para obtener los resultados que se muestran en el *Resumen*. Sin embargo la Script de Stacks funciona con esta submuestra y con los datos totales) 
*	Los archivos "popmap" y "popmapNS" con información referente a la población de procedencia de cada muestra, el primero separando por especies y el segundo separado por especie y por población norteña y sureña para el Script_Stacks. 
*	Un archivo "pob" necesario para el Script_SNPRelate.


____
**Bibliografia**

<sup>1</sup>Jezkova T, Riddle BR, Card DC, Schield DR, Eckstut ME, Castoe TA (2015) Genetic consequences of post-glacial range expansion in two codistributed rodents (genus Dipodomys) depend on ecology and genetic locus. Molecular Ecology 24(1): 83-97. http://dx.doi.org/10.1111/mec.13012

<sup>2</sup>Jezkova T, Riddle BR, Card DC, Schield DR, Eckstut ME, Castoe TA (2014) Data from: Genetic consequences of post-glacial range expansion in two codistributed rodents (genus Dipodomys) depend on ecology and genetic locus. Dryad Digital Repository. http://dx.doi.org/10.5061/dryad.1nv6k
___
