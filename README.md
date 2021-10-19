# AGP-Raw-Data
This repo serves to provide a consistent source for the URLs pointing to the raw data used to create the assemblies in the [ATCC Genome Portal](https://genomes.atcc.org). Our raw data is stored on MS Azure as a blob storage object. Here we provide a simple CSV that will be periodically be updated.

Columns in the CSV are:
1. **ATCC Strain ID**. For example _Escherichia coli_ (Migula) Castellani and Chalmers ATCC 11775 would simply be listed as "11775", and _Escherichia coli_ (Migula) Castellani and Chalmers BAA-2775 would simply be listed as "BAA-2755".
2. **URL** to MS Azure Blog Storage of raw FASTQs for both Illumina and ONT data for each assembly.
