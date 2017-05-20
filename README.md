### ARCHIVO EN CONSTRUCCIÓN

# Proyecto_Final-Bioinf2017-II
- Por: Israel Moreno-Contreras
__________

Este repositorio contiene datos tomados genómicos (RADseq) pre-procesados en formato .fastq de varios miembros del género *Piranga*, tomados de Manthey et al. (2016)<sup>1 2</sup> y disponibles en Genbank ("https://www.ncbi.nlm.nih.gov/sra/?term=Piranga"), con algunos outputs de interes y datos descriptivos en Dryad. También cuenta con algunos análisis de inferencia filogenética (Máxima verosimilitud, Parsimonia, y SVD quartets) empleando distintos parametros en ipyrad.

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
**Referencias**

<sup>1</sup>Manthey JD, Campillo LC, Burns KJ, Moyle RG (2016) Comparison of target-capture and restriction-site associated DNA sequencing for phylogenomics: a test in cardinalid tanagers (Aves, genus: Piranga). Systematic Biology 65(4): 640-650. http://dx.doi.org/10.1093/sysbio/syw005

<sup>2</sup>Manthey JD, Campillo LC, Burns KJ, Moyle RG (2016) Data from: Comparison of target-capture and restriction-site associated DNA sequencing for phylogenomics: a test in cardinalid tanagers (Aves, genus: Piranga). Dryad Digital Repository. http://dx.doi.org/10.5061/dryad.j5n06
___
