# AGP-Raw-Data
This repo serves to provide a consistent source for the URLs pointing to the raw data used to create the assemblies in the [ATCC Genome Portal](https://genomes.atcc.org). Our raw data is stored on MS Azure as a blob storage object. Here we provide a simple CSV that will be periodically updated.

By downloading genomics data from the ATCC Genome Portal, including raw sequencing data using the links contained in the CSV found in this repo, you are agreeing to the terms of ATCC's [Data Use Agreement](https://www.atcc.org/policies/product-use-policies/data-use-agreement). Essentially, the data is for Research Use Only and requires end users to register their use of the data by creating a user account at the [ATCC Genome Portal](https://genomes.atcc.org). 

Columns in the CSV are:
1. **Catalog Number**. For example _Escherichia coli_ (Migula) Castellani and Chalmers ATCC 11775 would simply be listed as "11775", and _Escherichia coli_ (Migula) Castellani and Chalmers BAA-2775 would simply be listed as "BAA-2755".
2. **Genome Tax ID**. NCBI's taxonomic identifier most closely related to this assembly.
3. **Assembly_URL** to MS Azure Blog Storage of raw FASTQs for both Illumina and ONT data for each assembly.
4. **Illumina_R1_URL** to the forward reads of paired Illumina data associated with each assembly
5. **Illumina_R2_URL** to the reverse reads of paired Illumina data associated with each assembly
6. **ONT_URL** to the Oxford Nanopore long reads associated with each assembly
