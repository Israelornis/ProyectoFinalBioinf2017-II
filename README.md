### ARCHIVO EN CONSTRUCCIÓN

# Proyecto_Final-Bioinf2017-II
- Por: Israel Moreno-Contreras
__________

Este repositorio contiene datos tomados genómicos (RADseq) pre-procesados en formato .fastq de varios miembros del género *Piranga*, tomados de Manthey et al. (2016)<sup>1 2</sup> y disponibles en Genbank ("https://www.ncbi.nlm.nih.gov/sra/?term=Piranga"), con algunos outputs de interes y datos descriptivos en Dryad. También cuenta con algunos análisis de inferencia filogenética (Máxima verosimilitud, Parsimonia, y SVD quartets) empleando distintos parametros en ipyrad.

En la carpeta **bin** se encuentran los scripts para:
 
1.	Realizar el llamado de los SNP´s y obtener los archivos de Ipyrad ver.0.6.19; con el comando **ipyrad -p params-ejemplo.txt -s 123**
2.	Hacer análisis comparativos de los estadísticos de los estadísticos descriptivos de los outputs arrojados por Ipyrad empleando distintos parámetros con R ver. 3.3.3.
3.	Hacer un árbol de máxima verosimilitud empleando RaxML. 
4.	Hacer un árbol no enraizado empleando SVDQuartets.
 
En la carpeta **data** se encuentra:

*	Una submuestra de los datos .fastq que se analizaron con el programa bioinformático Ipyrad (**Nota:** Estos datos son solo una parte de los datos que se utilizaron para obtener los resultados que se muestran en el *Resumen*. Sin embargo la Script de Ipyrad funciona con esta submuestra y con los datos totales) 
*	Los archivos en formato phylip para analizar en varios programas de inferencia filogenética "phylip" y "nexus" con información referente a lo datos obtenidos en Ipyrad y la número de pares de bases según el parámetro.


____
**Referencias**

<sup>1</sup>Manthey JD, Campillo LC, Burns KJ, Moyle RG (2016) Comparison of target-capture and restriction-site associated DNA sequencing for phylogenomics: a test in cardinalid tanagers (Aves, genus: Piranga). Systematic Biology 65(4): 640-650. http://dx.doi.org/10.1093/sysbio/syw005

<sup>2</sup>Manthey JD, Campillo LC, Burns KJ, Moyle RG (2016) Data from: Comparison of target-capture and restriction-site associated DNA sequencing for phylogenomics: a test in cardinalid tanagers (Aves, genus: Piranga). Dryad Digital Repository. http://dx.doi.org/10.5061/dryad.j5n06
___
