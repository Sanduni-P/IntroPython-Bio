
# Introduction

This introduction to Python workshop will provide beginners with experience loading, exploring, and visualising biological data using the pandas and matplotlib libraries. The example data used is clinical and gene expression data from the METABRIC breast cancer dataset, allowing participants to work with realistic biomedical data structures and learn how to generate meaningful summaries and plots.

# Instructor

Sanduni Rajapaksa

# Learning Objectives


By the end of this training, participants will be able to:

- Load tabular data into Python using pandas 
- Calculate basic statistics such as mean and median
- Filter and slice data based on clinical features
- Produce simple plots such as scatter plots and boxplots using matplotlib
- Modify the appearance of plots 

# Data

The Metabric study characterized the genomic mutations and gene expression profiles for 2509 primary breast tumours. In addition to the gene expression data generated using microarrays, genome-wide copy number profiles were obtained using SNP microarrays. Targeted sequencing was performed for 2509 primary breast tumours, along with 548 matched normals, using a panel of 173 of the most frequently mutated breast cancer genes as part of the Metabric study.

#### References: 

- [Curtis *et al.*, Nature 486:346-52, 2012](https://pubmed.ncbi.nlm.nih.gov/22522925)
- [Pereira *et al.*, Nature Communications 7:11479, 2016](https://www.ncbi.nlm.nih.gov/pubmed/27161491)

Both the clinical data and the gene expression values were downloaded from
[cBioPortal](https://www.cbioportal.org/study/summary?id=brca_metabric).

We excluded observations for patient tumor samples lacking expression data, resulting in a data set with fewer rows.

# Credits and Acknowledgements

This content was adapted from the following course materials:

 - [R for Data Science book](https://r4ds.had.co.nz/index.html)
 - [OHI Data Science Training](http://ohi-science.org/data-science-training/index.html)
 - [Data Carpentry](https://datacarpentry.org)
 - [WEHI tidyr coursebook](https://bookdown.org/ansellbr/WEHI_tidyR_course_book/) by Brendan R. E. Ansell
 - content developed by Maria Doyle.

------------------------------------------------------------------------
