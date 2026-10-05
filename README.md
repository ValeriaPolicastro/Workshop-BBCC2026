# Workshop-BBCC2026: Introduction to Biological Network Analysis and Robustness Assessment
This repository contains instructions and materials for the workshop

## Pipelines
We will follow 2 pipelines:

* Single cell ...
* Expression ...


## Data Availability
Please download the following folder:
* [Datasets Drive Folder]


## Sofware prerequisites
Required packages and software installation list:


### R software: 
* Latest R version https://www.r-project.org/
* Rstudio https://www.rstudio.com/

### R packages:

Open R\Rstudio and run the code highlighted

* R build tools
 ```
install.packages("rmarkdown")

```
* Robin
 ```
install.packages("robin")
install.packages("BiocManager")
BiocManager::install("BiocParallel")
```

* Seurat
```
install.packages("Seurat")
 ```




### Workshop Info:
Date:
October 21st, 9:00-13:00. The venue will be communicated to participants via email.

*Instructors: Annamaria Carissimo, Senior Researcher, Istituto per le Applicazione del Calcolo “M.Picone”, National Research Council of Italy, Naples, Italy; and Valeria Policastro, Junior Assistant Professor Department of Political Science, University of Naples ”Federico II”, Naples, Italy.*

*Tutorial Assistant: Domenico Sgambato PhD student at the University of Naples ”Federico II” , Vincenzo Della Gatta Research Fellow at National Research Council (CNR)*

*Short description* 

This tutorial will introduce the fundamental concepts of biological network analysis, including graph representation, network topology, community detection, and clustering evaluation. Participants will learn the principles of network robustness and explore how perturbation-based strategies can be used to assess the stability and reliability of community structures identified in biological networks. The tutorial will illustrate the idea that biologically meaningful communities should be preserved under controlled modifications of the network, whereas unstable partitions may indicate spurious or poorly supported patterns. Through hands-on examples, participants will learn how to evaluate the robustness of communities detected by different network clustering approaches, compare alternative network partitions, and interpret robustness measures in biological contexts. Applications to large-scale biological datasets, including single-cell transcriptomics data, will be presented to demonstrate how robustness analysis can improve the validation and interpretation of network-based discoveries.

*Requirements*

• Basic knowledge of R programming.
• Participants should bring a laptop with R and RStudio installed.
• No prior experience in network analysis is required.
