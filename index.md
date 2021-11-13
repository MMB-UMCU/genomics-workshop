---
---

![logo MMB-BioIT](/fig/logo.png) 
This is a fork of the [Data Carpentry Genomics workshop](https://datacarpentry.org/genomics-workshop/) for the MMB-BioIT group of the Medical Microbiology department, UMC Utrecht. Data Carpentry’s aim is to teach researchers basic concepts, skills, and tools for working
with data so that they can get more done in less time, and with less pain. This workshop
teaches data management and analysis for genomics research including: 
best practices for organization of bioinformatics projects and data, use of command-line 
utilities, use of command-line tools to analyze sequence quality and
perform variant calling.

> ## Frequently Asked Questions
> Read our [FAQ](/genomics-workshop/faq/) to learn more about Data Carpentry's Genomics workshop, as an Instructor or a workshop host.
{: .callout}

> ## Getting Started
>
> This lesson assumes that learners have no prior experience with the tools covered in the workshop. 
> However, learners are expected to have some familiarity with biological concepts,
> including the 
> concept of genomic variation within a population. Participants should bring their own laptops and plan to participate actively. 
> 
> 
{: .prereq}

> ## Data
> 
> This workshop uses data from a long term evolution experiment published in 2016: [Tempo and mode of genome evolution in a 50,000-generation experiment](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4988878/) by Tenaillon O, Barrick JE, Ribeck N, Deatherage DE, Blanchard JL, Dasgupta A, Wu GC, Wielgoss S, Cruveiller S, Médigue C, Schneider D, and Lenski RE. (doi: 10.1038/nature18959)
>
> All of the data used in this workshop can be [downloaded from Figshare](https://figshare.com/articles/Data_Carpentry_Genomics_beta_2_0/7726454). 
> More information about this data is available on the [Data page](https://datacarpentry.org/organization-genomics/data/).
{: .prereq} 

# Workshop Overview 

| Time  | Lesson | Overview |
| ------- | ---------- |
| Day 1 morning | [Project organization and management](https://mmb-umcu.github.io/organization-genomics/) | Learn how to structure your metadata, organize and document your genomics data and bioinformatics workflow, and access data on the NCBI sequence read archive (SRA) database.|
| Day 1 afternoon |[Introduction to the command line](https://mmb-umcu.github.io/shell-genomics/) |  Learn to navigate your file system, create, copy, move, and remove files and directories, and automate repetitive tasks using scripts and wildcards. |
| Day 2 and 3 | [Data wrangling and processing](https://mmb-umcu.github.io/wrangling-genomics/) | Use command-line tools to perform quality control, align reads to a reference genome, and identify and visualize between-sample variation. |

# Optional Additional Lessons (day 3 and self-study)

| Lesson | Overview |
| ------- | -------- |
| [Bash scripting exercises: grep](https://ryanstutorials.net/linuxtutorial/grep.php) | Learn grep and regular expressions with examples 
| [Bash scripting exercises: sed](https://www.tutorialspoint.com/sed/) | sed tutorial for advanced learners
| [Bash scripting exercises: awk](https://www.tutorialspoint.com/sed/) | awk tutorial with many examples 
| [Putting your grep/sed/awk knowledge to the test](https://www.hackerrank.com/domains/shell?filters%5Bsubdomains%5D%5B%5D=grep-sed-awk) | Challenges for grep/sed/awk programmers. Requires a user account at [hackerrank](http://www.hackerrank.com)
| [Introduction to cloud computing for genomics](http://www.datacarpentry.org/cloud-genomics/) | Learn how to work with Amazon AWS cloud computing and how to transfer data between your local computer and cloud resources. 
| [Intro to R and RStudio for Genomics](https://datacarpentry.org/genomics-r-intro/) | Use R to analyze and visualize between-sample variation. Please note that workshop materials for working with Genomics data in R are in “alpha” development.|
| [R for reproducible scientific analyses](https://swcarpentry.github.io/r-novice-gapminder/) | Fundamentals in R and tidyverse |



# Teaching Platform
This workshop is designed to be run on pre-imaged Amazon Web Services (AWS)
instances. All the software and data used in the workshop are hosted on an Amazon Machine Image (AMI).
If you want to run your own instance of the server used for this workshop, follow the directions in the [Setup](setup.html) tab. 

