# Files Description

Version：v1;
Update：2024/4/9.

## Files in the /data folder
Files description:
- /qc folder

**A /qc folder saved QC data from MultiQC and FastQC**
- /qc/multiqc_report.zip

**The zip file for "multiqc_report.html", readers with interest should uzip this file to read the QC report of all sequences.**
- /qc/multiqc_report_data

**In the /qc folder, there is a /multiqc_report_data folder containing source data of "multiqc_report.html", including multiqc_fastqc.txt, multiqc_general_stats.txt, multiqc_sources.txt**
- 1.16S.ASV.profile.original.rds

**The original 16S rRNA ASV profile**
- 1.sample.info.original.rds

**The sample information (metadata) for the 1000RA cohort**
- 1.taxonomy.info.rds

**The taxonomy information of the 16S rRNA ASV; the ASVs were anotated at the phylum, class, order, family, genus and species levels.**
- 2-1.stackplot_group_HC.txt

**Taxonomy data for HC group at the genus level, top 23 genera and others**
- 2-1.stackplot_group_RA.txt

**Taxonomy data for RA group at the genus level, top 23 genera and others**
- 2-1.stackplot_sample_HC.txt

**Taxonomy data for all samples in the HC group at the genus level, top 23 genera and others**
- 2-1.stackplot_sample_RA.txt

**Taxonomy data for all samples in the RA group at the genus level, top 23 genera and others**
- 2-1a.tax_6Genus0.001_HC.txt

**Taxonomy data for HC group, presenting all genera with abundance over 0.1%**
- 2-1a.tax_6Genus0.001_RA.txt

**Taxonomy data for RA group, presenting all genera with abundance over 0.1%**
- 2-1b.HC.cuttree.txt

**Sample clustering for HC group**
- 2-1b.RA.cuttree.txt

**Sample clustering for RA group**
- 2-2.bray_curtis.rds

**Beta diversity matrix**

## Files in the /script folder
Files description:
- 1.tax_stackplot.Rmd                 

**The Rmarkdown file for visualization code for stackplot in the Group and the Sample condition**
- 2.3D-CPcoa.Rmd

**The Rmarkdown file for beta diversity visualization**




Copyright 2024-2026 Jun Xu <xujun@hsc.pku.edu.cn>
