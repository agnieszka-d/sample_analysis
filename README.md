# sample_analysis  
Sample RNA-Seq analysis workflow  
# Installation  
The following packages are required for running this analysis:  
Knitr and markdown:   
install.packages("rmarkdown")  
install.packages("knitr")  
  
Bioconductor packages:  
source("https://bioconductor.org/biocLite.R")  
biocLite("DESeq2")  
biocLite("airway")  
biocLite("biomaRt")  
biocLite("pheatmap")  
  
Ggplot2 and reshape2:  
install.packages("ggplot2")  
install.packages("reshape2")  

Please refer to the packages_to_install.Rmd file prior to runningn the sample_RNA-Seq_analysis.Rmd script.    
# Usage  
This sample analysis is written in an R Markdown document, intended to be executed in RStudio with R version 3.3.  
