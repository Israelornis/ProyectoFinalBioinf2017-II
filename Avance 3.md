# Avances 3

## Diario de trabajo
Anteriormente (ver Avances 1 y 2) yo estaba interesado en hacer análsis de genética de poblaciones usando los datos genómicos (ddRAD) de *Ammodramus nelsoni* y *Ammodramus caudacutus* de Walsh et al. (2017) disponibles en Dryad. No obstante despues de una revisión en el material suplementario y en el repositorio de Dryad no se encuentran disponibles los barcode, esenciales para los análisis en el programa bioinformático Ipyrad. Bajo esta premisa, decidí cambiar de datos empleando los datos genómicos del género *Piranga*  (RAD-seq) de Manthey et al. (2016), enfocandome en análisis de filogenómica y ya no de genética de poblaciones.
He tenido algunos problemas con los datos, pero el lunes me quede de ver con Azalea para ver que es lo que está fallando. Espero resolverlo para mediados de la próxima semana.

**Tipo de datos:** Ddatos genómicos del género *Piranga*  (RAD-seq) de Manthey et al. (2016) disponibles en Genbank (https://www.ncbi.nlm.nih.gov/sra/?term=Piranga), con algunos datos descriptivos en Dryad.

| Actividad     | Estado |
| ------------- |:-------------:|
| Descargar datos del repositorio Dryad     | Listo  |
| Montar un volumen en docker para analizar los datos     | Listo   | 
| Instalar ipyrad | Listo |   
| Instalar RAxML | Listo |  
| Instalar PAUP | Listo |
| Análisis de máxima verosimilitud | Pendiente |  
| Organizar repositorio | Pendiente |
|[README](https://github.com/Israelornis/ProyectoFinalBioinf2017-II/blob/master/README.md) | <span style="color:red"> Pendiente</span> |

### Artículos leídos

+ Dierickx, E.G., A.J. Shultz, F. Sato, T. Hiraoka T y S.V. Edwards SV. 2015. Morphological and genomic comparisons of Hawaiian and Japanese Black-footed Albatrosses (*Phoebastria nigripes*) using double digest RADseq: implications for conservation. Evolutionary Applications 8(7): 662-678. http://dx.doi.org/10.1111/eva.12274

+ Friis, G., P. Aleixandre, R. Rodríguez-Estrella, A.G. Navarro-Sigüenza y Borja Milá. 2016. Rapid postglacial diversification and long-term stasis within the songbird genus *Junco*: phylogeographic and phylogenomic evidence. Molecular Ecology 25(24): 6175-6195. http://dx.doi.org/10.1111/mec.13911

+ Harvey, M.G. y R.T. Brumfield. 2015. Genomic variation in a widespread Neotropical bird (*Xenops minutus*) reveals divergence, population expansion, and gene flow, Molecular Phylogenetics and Evolution 83(2014): 305-316. doi: http://dx.doi.org/10.1016/j.ympev.2014.10.023

+ Manthey, J.D., L.C. Campillo, K.J. Burns y R.G. Moyle. 2016. Comparison of target-capture and restriction-site associated DNA sequencing for phylogenomics: a test in cardinalid tanagers (Aves, genus: *Piranga*). Systematic Biology 65(4): 640-650. http://dx.doi.org/10.1093/sysbio/syw005

+ Mason, N.A. y S.A. Taylor. 2015. Differentially expressed genes match bill morphology and plumage despite largely homogenous genomes in a Holarctic songbird. Molecular Ecology 24(12): 3009-3025. http://dx.doi.org/10.1111/mec.13140

+ Oswald, J.A., I. Overcast, W.M. Mauck III, M.J. Andersen y B.T. Smith. 2017. Isolation with asymmetric gene flow during the nonsynchronous divergence of dry forest birds. Molecular Ecology 26(5): 1386-1400. http://dx.doi.org/10.1111/mec.14013

+ Parchman, T.L., C.A. Buerkle, V. Soria-Carrasco y C.W. Benkman. 2016. Genome divergence and diversification within a geographic mosaic of coevolution. Molecular Ecology 25(22): 5705-5718. http://dx.doi.org/10.1111/mec.13825

+ Toews, D.P.L., L. Campagna, S.A. Taylor, C.N. Balakrishnan, D.T. Baldassarre, P.E. Deane-Coe, M.G. Harvey, D.M. Hooper, D.E. Irwin, C.D. Judy, N.A. Mason, J.E. McCormack, K.G. McCracken, C.H. Oliveros, R.J. Safran, E.S.C. Scordato, K.F. Stryjewski, A. Tigano, J.A.C. Uy y B.M. Winger. 2016. Genomic approaches to understanding population divergence and speciation in birds. The Auk 133(1): 13-30. http://dx.doi.org/10.1642/AUK-15-51.1

+ Walsh, J., I.J. Lovette, V. Winder, C.S. Elphick, B.J. Olsen, G. Shriver y A.I. Kovach. 2017. Subspecies delineation amid phenotypic, geographic and genetic discordance in a songbird. Molecular Ecology 26(5): 1242-1255. http://dx.doi.org/10.1111/mec.14010


### Datos y análisis
+ Manthey JD, Campillo LC, Burns KJ, Moyle RG (2016) Data from: Comparison of target-capture and restriction-site associated DNA sequencing for phylogenomics: a test in cardinalid tanagers (Aves, genus: Piranga). Dryad Digital Repository. http://dx.doi.org/10.5061/dryad.j5n06

**Análisis a realizar:** Se realizarán algunos análisis de Filogenómica empleando distintos parametros en Ipryrad: Máxima Verosimilitud, SVD quartets. Se harán gráficas para ver que tanto influyen los parámetros en la obtención de pares de bases.
