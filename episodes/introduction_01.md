---
title: "Introduction to microbiome data management using MGnify"
teaching: 10
exercises: 1
---

## Summary and setup

This leason focuses on methods and issue surrounding the use and management of microbiome data.
It is aimed at beginners to microbiome data, but for those who have run some analysis of their own
Learners are expected to be familier with analysis pipelines such as QIIME2. For details on these pipelines you can find many excellent tutorials and .....

:::::::::::::::::::::::::::::::::::::: Question

- Are there any specific features relating to microbome data analysis?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Understand the speicfic issues of data management relating to microbiome datasets
- Access Mgnify and retrive data
- Submit data for analysis to Mgnify
- Manage QIIME2 outputs 

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction to microbiome data management using MGnify

Microbiome analysis can be broadly split into two types: targeted sequencing (also known as amplicon), and shotgun sequencing. Amplicon sequencing relies on using a marker gene (for example 16SrRNA or ITS), amplifying regions of these genes that are hypervariable which allows identification. The data from this technique gives a reliable snapshot of the microbiome with ~70% of the features being identified to the genus taxonomic level. The data from these experiments can range from 1-50+ Mb in size making it easy to store and analyse. Shotgun sequencing, however, results in much larger files and complex analysis. The data from a shotgun sequencing method far exceeds that of amplicon sequencing, with features being identified to species level and file sizes exceeding 1 GB in size.

Microbiome research was revolutionized by increasing sequencing power, with amplicon sequencing being a cheaper and a reliable snapshot of a microbial community in an environmental sample. As sequencing depths have increased, shallow shotgun and deep sequencing approaches may increase in popularity. Other developments such as long-read systems also offer potential improvements.

The study metadata for a microbiome study, like any other sequencing data set, is essential for data management. However, there are a number of specific features of a microbiome study that need to be recorded to enable full and meaningful analysis. 

Depending on the microbiome analysis method, there is also a wide variety of analysis pipelines, utilizing different languages and platforms. QIIME2 is a popular, highly user-friendly analysis pipeline, but can lead to many outputs (QZA and QZV files). QIIME2 also has a built-in method for tracking the data workflow, but it can be very confusing with a large number of files. Using DADA2 workflows in R also give their own management problems.

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

Inline instructor notes can help inform instructors of timing challenges
associated with the lessons. They appear in the "Instructor View"

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: challenge 

## Question: 

Can you identify and specific elements of microbiome data  management? 

:::::::::::::::::::::::::::::::::::::


In these training materials, we will cover the major aspects of managing a microbiome analysis project, some of which may be similar to other sequencing projects, but there are many unique features to microbiome data analysis.

-Metadata and prepocessing 
Microbiome metadata 
File manifests
Preprocessing, Sequencing primers,Demultiplexing
- Using Google Colab/Google cloud  to store and move data
MGnify and ENA
-Analysis pipelines and data management 
Managing QIIME2 outputs
-Submitting data to Mgnify
-Retrieving data from Mgnify



::::::::::::::::::::::::::::::::::::: keypoints 

- There are two major paradigms in microbiome technologies, amplicon and shotgun sequencing
- There are many analysis pipelines, each one with its one unique data management challenge 

::::::::::::::::::::::::::::::::::::::::::::::::

[r-markdown]: https://rmarkdown.rstudio.com/
