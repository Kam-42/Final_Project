# Final_Project
These are files associated with my final project's reproducible workflow. 

## Pipeline Diagram
![Workflow Diagram](workflow_diagram.png)

## Bioinformatics Tools Used
-Trimmomatic
-FastQC
-Kraken2
-Trinity de novo Assembly
-BLASTn Database



## Repository Structure
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