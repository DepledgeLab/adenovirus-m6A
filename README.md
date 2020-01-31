# adenovirus-m6A
Datasets associated with our study of m6A modified adenoviral mRNAs

Description of files

* The .zip files each contain three text files containing output from the m6A analysis of dRNA-Seq datasets. 

M3P1-M3KO1.m6A.botstrand.complete.txt
-- output file from analysis of dRNA-Seq reads that align against the bottom strand of the Ad5 genome

M3P1-M3KO1.m6A.topstrand.complete.txt
-- output file from analysis of dRNA-Seq reads that align against the top strand of the Ad5 genome

M3P1-M3KO1.m6A.transcripts.complete.txt
-- output file from analysis of dRNA-Seq reads that align against Ad5 encoded polyadenylated RNAs

Note that the context of the comparison is described in the filename. e.g. the comparison between Ad5-infected A549 cells (parent) biorep #1 and Ad5-infected A549 cells (METTL3 k.o.) biorep #1 is described as M3P1-M3KO1


* The .bedgraph files are generated in a stranded manner from dRNA-Seq datasets aligned against the Ad5 genome (i.e. one file per strand) with 'forward' denoting the top strand and 'reverse' denoting the bottom strand

* The meRIP_adenovirus_bedgraphs.zip file contains bedgraph files generated from aligning (Illumina short-read) meRIP-Seq data against the Ad5 adenovirus genome. Three biological replicates for each condition (input / meRIP) are included for virus-infected and mock-infected samples.
