Genomic Algorithms Week 1 Project
============================
Course beings with identifying two core problems in Genomics that we use algorithms to solve. The first problem is related to aligning new reads to reference genomes.

Sequencing Files
————————
All raw FASTA and FASTQ sequences are in data/FASTA_q files:


Quality Control Steps
———————————
After sequence data downloaded first step with FASTQ was to check for quality of reads. We ran each line through quality diagnostic and control pipeline. Our planned pipeline is:
	1.	Create base quality diagnostic graphs
	2.	Check reads for adapter sequences
	3.	Trim adapter sequences
	4.	Trim poor quality bases

Recommended trimming programs:
	▪	Trimmomatic
	▪	Scythe
