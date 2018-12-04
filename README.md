# genomics
Genome analysis of rhizobia and other bacteria

# Jigome
This script takes sets of contigs assembled by SPAdes and carries out further assembly to 
create larger scaffolds.  Assembly is guided by the connections in the contig graph and by
homologous links found a set of reference genomes.  The chromosomal contigs are oriented
and ordered using a set of core genes that have the same order in all members of a set of
fully-assembled genomes. Plasmid replication genes are identified and used to label the
corresponding scaffolds.
The current version is specific for genomes of Rhizobium leguminosarum, but it could be modified for use with other bacteria.
