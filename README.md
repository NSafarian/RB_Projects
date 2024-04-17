## RBA_Project
This repo contains descriptions and codes related to Regional Burden Analysis (RBA) method.

# Step-by-step tutorial for QC of WES dataset:
To ensure the successful execution of this tutorial, it's essential that the data structure/format and QC variables align with those utilized herein. In this tutorial we'll use the annotated format of WES data which consist of separate files for each individual sample. For instance, the SP0000017.tsv data file in the SPARK_WES2 cohort represents WES data for **sample ID** SP000017, formatted as a tab-delimited file (**.tsv**). If the data isn't organized on a per-individual basis, is aggregated across samples per chromosome, or if is in a .vcf format, adjustments in the codes may be necessary. At times, all QC metrics might not be included in the annotated files, necessitating a check for the available variables. 
