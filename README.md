# SRA_Virus_Mining
This pipeline was created to mine SRA data sets for virus sequences

It consists of three nextflow modules that have been independently created by other users. First it downloads SRA datasets based on a list of desired SRA accessions you give it using the nf-core fetchngs module. It then takes the raw files and pre-processes them using the Stenglein Lab's read pre-processing_workflow. Finally, it aligns reads to a fasta file with the desired virus sequence you want to capture using the Stenglein Lab's remapping_workflow.
