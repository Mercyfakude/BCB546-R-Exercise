---
title: "GCarey_Comments"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## R Markdown

I ran into an issue with reading the files into R. Your OneDrive link is not accessible to me, so I substituted these open links into the script and it ran well. 


```{r cars}
fang.mf <- read.delim("https://raw.githubusercontent.com/EEOB-BioData/BCB546-Spring2022/main/assignments/UNIX_Assignment/fang_et_al_genotypes.txt", header = TRUE)
snp.mf <- read.delim ("https://raw.githubusercontent.com/EEOB-BioData/BCB546-Spring2022/main/assignments/UNIX_Assignment/snp_position.txt", header = TRUE)
```

I really like your purple and yellow Snp Count Per Chromosome plot! I changed the title to include capitalization (maybe a matter of personal preference). 

For "Ratio of homozygotes, heterozygotes and missing data by genotype" figure, it doesn't appear to be sorted or labeled by Genotype. It was interesting to see how the Homozygotes/Heterozygotes/Missing data was distributed, but the graph would be more informative with Genotypes included, if that is what you're aiming for.As it stands, this seems to be a figure sorting zygosity by sample ID. 
I edited the title (Ratio of homozygotes, heterozygotes and missing data by Sample ID) to reflect this. 

You have a concise and creative way of sorting by chromosome and making files. However, I can't view columns or see how well sorted they are, or view any meaningful information from them. I can't tell if your sorting worked or if your data is correct. There may be a way to view the files correctly using R or another program, but I am having trouble figuring that out. I tried to export as a .csv and the data was slightly more readable this way, but only slightly. Any changes on this front would be appreciated. Additionally, if you have an efficient way to view these files, I'd love to hear about it (I have a lot to learn in R yet).

You could try exporting individual files using "write.csv()", although this is more labor intensive than your current setup. 

Overall, good job and nice visualizations!
