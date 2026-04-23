# Final_Project
These are tools and files associated with my final project's reproducible workflow. 

## Packages to be installed on R studio
- knitr
- ggplot2
- dplyr
- tidyr

## Raw Data
- Raw data for each sample consist of two files (forward and reverse RNA sequence reads) each 1-2GB in size, and there are seven samples being analyzed.  
- Raw data for samples are not here on github due to being unreadible and large files. Those raw sequence reads are available via Final_Project folder that was sent to Dr. Noel. 
- Resulting Assembled Transcripts are also available via the Final_Project folder sent to Dr. Noel but not on github due to size and unreadability.
- IMPORTANT: The starting raw data input at the beginning of the workflow is SoybeanX_R1combined.fastq.gz and SoybeanX_R2combined.fastq.gz


## Bioinformatics Tools Used 
#### Version Control listed in sample workflows.
-Trimmomatic
-FastQC
-Kraken2
-Trinity 
-BLASTn Web Database 

## Wet lab experiments used
- Polymerase Chain Reaction for target virus amplification
- Gel Electrophoresis to validate target virus was amplified



## 'Final_Project' Folder Structure
```
Final_Project/
├── Final_Project.Rproj
├── README.md
├── Results_Final.md
├── workflow_diagram.png
│
├── Samples_Raw_Data/
│   ├── SB1/
│   │   ├── SB1_R1_combined.fastq (1).gz
│   │   └── SB1_R2_Combined.fastq (1).gz
│   │
│   ├── SB2-3/
│   │   ├── SB2-3_R1_combined.fastq (1).gz
│   │   └── SB2-3_R2_Combined.fastq (1).gz
│   │
│   ├── SB5/
│   │   ├── SB5_R1_combined.fastq (1).gz
│   │   └── SB5_R2_Combined.fastq (1).gz
│   │
│   ├── SB6/
│   │   ├── SB6_R1_combined.fastq (1).gz
│   │   └── SB6_R2_Combined.fastq (1).gz
│   │
│   ├── SB7-8/
│   │   ├── SB7-8_R1_combined.fastq (1).gz
│   │   └── SB7-8_R2_Combined.fastq (1).gz
│   │
│   ├── SB9/
│   │   ├── SB9_R1_combined.fastq (1).gz
│   │   └── SB9_R2_Combined.fastq (1).gz
│   │
│   └── SB10/
│       ├── SB10_R1_combined.fastq (1).gz
│       └── SB10_R2_Combined.fastq (1).gz
│
├── Reproducible_Workflows/
│   ├── SB1_Workflow.Rmd
│   ├── SB2-3_Workflow.Rmd
│   ├── SB5_Workflow.Rmd
│   ├── SB6_Workflow.Rmd
│   ├── SB7-8_Workflow.Rmd
│   ├── SB9_Workflow.Rmd
│   └── SB10_Workflow.Rmd
│
└── Assembled_Transcripts/
    ├── SB1transcripts_1000bp.fasta
    ├── SB2-3 Assembled Transcripts with matched ID.fasta
    ├── 
    ├── SB6AssembledTranscripts.fasta
    ├── SB7-8AssembledTranscripts.fasta
    ├── SB9AssembledTranscripts.fasta
    └── SB10AssembledTranscripts.fasta
```