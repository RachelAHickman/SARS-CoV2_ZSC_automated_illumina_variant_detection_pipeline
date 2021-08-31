# SARS-CoV2_ZSC_automated_illumina_variant_detection_pipeline

In the Zoonosis Science Center - Uppsala University a illumina amplicon sequencing based method and compuational work-flow that has been developed Jiaxin Ling and Rachel Hickman.

The compulational pipeline is designed to run on the UPPMAX computer cluster and uses snakemake as the workflow management system tool (Mölder F, Jablonski KP, Letcher B et al. Sustainable data analysis with Snakemake [version 1; peer review: 1 approved, 1 approved with reservations]. F1000Research 2021, 10:33 (https://doi.org/10.12688/f1000research.29032.1)).

Dependices that are need are:
- Graphviz 2.40.1
- Java sun_jdk1.8.0_151
- FastQC 0.11.9 
- MultiQC 1.9 
- blast 2.9.0+ 
- Pilon 1.22 
- samtools 1.10  
- bowtie2 2.3.5.1 
- TrimGalore 0.6.1
- Breseq 0.36.0

The raw illumina data generated was a collaborative effort between Jiaxin Ling, Rachel Hickman, Douglas Husby, Åke Lundkvist, Josef Järhult and Diarmaid Hughes and can be obtained under the SRA project accession number.
