#Genetic Determinants

## This repository contains open-source code, data, and text files for the genetic determinants project

## Repository contents
gen-dets_analysis.Rmd

### breseq
	**genome_diff**: directory containing the genome diff files for each strain analyzed with breseq 
	*gsaf_illumina_adapters.fasta*: Illumina adapter sequences
	*NC_009481.1.gbk*: NCBI *Synechococcus sp WH7803* genome
	*syn-ancestor.gff*: updated *Synechococcus* reference genome for project. See expanc-breseq.sh for script.
	*example-script.sh*: example script for the *breseq* analysis of each mutant genome
	*sequences_metadata.csv*: contains information pertaining to strain sequencing at MSU RTSF. Column headings are as follows: 

		- strain_id: alphanumeric code assigned to each isolate corresponding to its isolation time point (e.g., 01), the replicate chemostat from which it was isolated (e.g., N2), and the isolate number (e.g., S4).
		- seq.date: date in which sequencing was completed
		- seq.platform: Illumina HiSeq with single end 100 bp reads or Illumin MiSeq with paired end 250 bp reads
		- gDNA.conc: genomic DNA concentration (ng/uL) of sample submitted to RTSF
		- A260/A280
		- DNA.kit: kit used for DNA amplification at MSU RTSF
		- cstat.trt: designation for chemostats with the addition (+Ph) or lack of (-Ph) phage
		- cstat.lim: nutrient limiting regime; N = nitrogen-limited, P = phosphorus-limited
		- cstat.id: replicate chemostat identifier
		- cstat.time: time point in which strain was isolated

### data
	*bor*: breadth of resistance; matrix containing infectivity data for all strains. Cyanobacteria are in each column, phage are in each row
	*breseq.compare*: matrix of genomic mutations predicted by breseq between strains
	*genes*: genomic information for genes of interest
	*mutations*:
	*mut-cts*:
	*strains*:

### supporting-files
#### data
#### figures