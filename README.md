# coastal_chinook_2020_analysis

This is the parent repository for all 2020 Oregon Coast Chinook analyses.

## Rationale
The primary goal for this project is to characterize genetic variation at run-timing associated genetic markers among 2020 Oregon Coast Chinook populations using GTseq.

## TOC
Several notebooks and directories are contained here.  

### Directories:  
* __~/run_genotyping:__ individual illumina run genotyping information, some runs were previously genotyped, they are here, but not used  
  * __run 018:__  
  * __run 021:__  
  * __run 025:__  
* __~/project_genotyping:__ this directory contains the joint genotyping log and results  
* __~/metadata:__ project metadata  
  * __intake_forms :__ raw intake data  
  * __consolidated_metadata:__  cleaned up metadata  
  * __seq_data:__ library prep information  
  * __bohn:__ Sandra Bohn's metadata
* __~/analyses:__ all data analysis after genotype calling and filtering  
  * __~/analyses/genotype_vis:__  presentation of filtered data with no analysis, by basin

### Notebooks
* __Combining_metadata.rmd:__ log of combining sample intake forms, progeny entries etc into a single document with unified field names  
* __2020_OC_Chinook_Genotyping_Notebook.html__: genotyping notebook - raw reads to filtered genotypes