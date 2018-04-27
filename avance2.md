# Avance 2

**Alondra Karina Terrones Ramírez**

Hasta el momento lo que he hecho principalmente es una investigación en la literatura, he leído una serie de artículos donde han trabajado con secuencias RADseq y con un enfoque hacia filogenias-filogeografía. 

El patrón que he encontrado es que la mayoría han hecho el procesamiento de las secuencias con el programa STACKS (por ejemplo, Saenz-Agudelo et al., 2015, Manthey et al., 2016 y Xang et al., 2017), sin embargo, en la actualidad es más recomendable usar el programa PyRAD ya que tiene la ventaja de que está diseñado para reunir datos para estudios filogenéticos que contienen especies divergentes utilizando clusters de alineación global, que puede incluir variación indeleble (Leaché et al., 2015). 

Respecto a las reconstrucciones filogenéticas, he encontrado que han usado distintos programas, por ejemplo programas que usan un modelo coalescente como SDVquartets y SNAPP (Manthey et al., 2016, Xang et al., 2017; Leaché et al., 2015),  y hay otros autores que realizan las filogenias con programas como TREEMIX, RAxML y PhyML (Cruaud et al., 2014; Xang et al., 2017). Lo que he investigado (y observado en los artículos) es que si es para análisis a nivel interespecifico se recomienda programas como SDVquartets y SNAPP, y si es para análisis intraespecificos es recomendable TREEMIX. 

Para hacer el análisis de componentes principales de los genotipos, se utiliza la función dudi.pca (en R Project), y ya he leído un poco acerca de esta función.

Intente bajar las secuencias RAD de NCBI con “wget” pero no pude, por lo que he estado leyendo “Downloading SRA data using command line utilities” para poder bajar las secuencias desde la línea de comandos. 
Por otro lado, he llegado a la conclusión que no haré todo lo que dije en al avance 1, y solo hare una reconstrucción filogenética y/o el análisis de componentes principales de los genotipos, esto es debido a falta de tiempo  y experiencia, además considero que es suficiente hacer solo un análisis (y no los tres que había propuesto en el avance 1). 

Cruaud, A. et al. (2014). Empirical assessment of RAD sequencing for interspecific phylogeny. Mol. Biol. Evol. 31, 1272–1274.

Leaché A.D., Chavez A.S., Jones L.N., Grummer J.A., Gottscho A.D., Linkem C.W. 2015. Phylogenomics of Phrynosomatid lizards: Conflicting signals from sequence capture versus restriction site associated DNA sequencing. Genome Biol. Evol. 7:706–719.

Manthey J.D.,Campillo L.C., Burns K.J.,Moyle R.G. 2016.Comparison of target capture and restriction-site associatedDNAsequencing for phylogenomics:Atest inCardinalidtanagers (Aves,Genus:Piranga).

Saenz-Agudelo, P., Dibattista, J.D., Piatek, M.J., Gaither, M.R., Harrison, H.B., Nanninga, G.B., Berumen, M.L. 2015. Seascape genetics along environmental gradients in the Arabian Penin- sula: insights from ddRAD sequencing of anemonefishes. Mol. Ecol. 24: 6241-6255.

Wang X., Ye X., Zhao L., Li Dezhu., Guo Z., y Zhuang H., (2017). Genome-wide RAD sequencing data provide unprecedented resolution of the phylogeny of temperate bamboos (Poaceae: Bambusoideae). Scientific Reports. 
