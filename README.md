# differential-expression

There are 2 files in this repository: Python processing, and R analysis.
Due to a lack of computing/processing power, the Python processing workflow was only evaluated with a single-end FASTQ and chr22. With a full reference chromosome, the workflow functions well, but runs slowly and takes a while to complete. The run time is even longer (at least a day) with paired-end FASTQs.
Without featureCounts or another method to quantify expression from raw FASTQ, the R workflow takes a public dataset and performs exploratory data analysis (PCA, clustering) as well as differential expression analysis in order to identify differentially expression genes. This workflow was used to identify biomarkers in glioblastoma from microarray data (can be found in Writing-Samples)
