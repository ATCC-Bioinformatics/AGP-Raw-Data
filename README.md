# AGP-Raw-Data
This repo serves to provide a consistent source for the URLs pointing to the raw data used to create the assemblies in the [ATCC Genome Portal](https://genomes.atcc.org). Our raw data is stored on MS Azure as a blob storage object. Here we provide a simple CSV that will be periodically be updated.

Columns in the CSV are:
1. ATCC Strain Name / ATCC Product ID. For example _Thermococcus zilligii_ Ronimus et al. ATCC 700529 would simply be listed as "700529")
2. URL to MS Azure Blog Storage of raw FASTQ for both Illumina and ONT data for this assembly.
