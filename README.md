# Seminar paper on clustering of weighted graphs using the PaCCo algorithm
Seminar paper (@Technical University Munich) on parameter free clustering of weighted graphds using the PaCCo algorithm (Parameter-free Clustering by Coding costs)).

The PaCCo algorithm was originally conceptualized and devised by:
Mueller, N.S., Haegler, K., Shao, J., Plant, C. and Böhm, C., 2011, April. Weighted graph compression for parameter-free clustering with pacco. In Proceedings of the 2011 SIAM International Conference on Data Mining (pp. 932-943). Society for Industrial and Applied Mathematics.
https://pdfs.semanticscholar.org/21f3/5d96e7854e1d41ba7e1e1f0c33886719af7c.pdf

**ABSTRACT**

Since the first decade of the 21st century network science is undergoing a huge increase of popularity. [1]
Data in form of graphs is increasingly used to observe behavior of agents in networks, to find inter-object interactions
and to map out objects like diseases [2] to use the network’s topology to discover subtle relationships that might not be
discovered otherwise. Weighted graphs enrich these findings by adding a dimension of interaction strength and allowing
for deeper understanding of object interaction. With the rising amount of data, elaborate algorithms are needed to find
structures and patterns within the graphs to facilitate analysis and interpretation. One very important tool used is the
clustering of graphs to detect interesting and meaningful substructures to make sense of the data. But most state of the
art clustering algorithms require input parameters like the expected number of clusters. This creates the need to compute
the approximate number of clusters in beforehand thus complicating the utilization of such algorithms and their application
on real world data as well as research. This paper is presenting and analyzing the PaCCo (Parameter-free Clustering by
Coding costs) algorithm as introduced by Mueller et al. [3] that overcomes those issues by using the Minimum Description
Length (MDL) principle together with a bisecting k-Means approach to automatically and parameter independently cluster
weighted graphs on the basis of coding costs and data compression.


**REFERENCES**

[1] A.-L. Barabsi, M. Martino, M. Psfai, and P. Hvel, Network
Science. self published online, 2012.

[2] K.-I. Goh, M. E. Cusick, D. Valle, B. Childs, M. Vidal,
and A.-L. Barabsi, “The human disease network,” Proceedings of the National Academy of Sciences, vol. 104, no. 21, pp. 8685–8690, 2007. [Online]. Available:http://www.pnas.org/content/104/21/8685.abstract

[3] N. Mueller, K. Haegler, J. Shao, C. Plant, and C. Böhm, “Weighted graph compression for parameter-free clustering with pacco.” in SDM. SIAM, 2011, pp. 932–943.

[4] L. Zelnik-Manor and P. Perona, “Self-tuning spectral clustering.” in NIPS, vol. 17, no. 1601-1608, 2004, p. 16.

[5] S. v. Dongen, “A cluster algorithm for graphs,” Information Systems [INS], no. R 0010, pp. 1–40, 2000.

[6] G. Karypis and V. Kumar, “A software package for partitioning unstructured graphs, partitioning meshes, and
computing fill-reducing orderings of sparse matrices,” 1998.

[7] D. Chakrabarti, S. Papadimitriou, D. S. Modha, and C. Faloutsos, “Fully automatic cross-associations,” in In
KDD, 2004.

[8] J. Rissanen, “Modeling by shortest data description,” Automatica, vol. 14, no. 5, pp. 465–471, 1978.

[9] ——, “Minimum description length principle,” in Encyclopedia of Machine Learning, C. Sammut and G. Webb,
Eds. Springer US, 2010, pp. 666–668. 

[10] T. A. Runkler, “Clustering,” in Data Analytics. Vieweg+Teubner Verlag, 2012, pp. 103–122.

[11] S. Miyamoto and K. Umayahara, “Methods in hard and fuzzy clustering,” in Soft Computing and Human-Centered Machines, ser. Computer Science Workbench, Z.-Q. Liu and S. Miyamoto, Eds. Springer Japan, 2000, pp. 119–125.
