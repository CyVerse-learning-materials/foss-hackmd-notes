---
tags: foss-fall-21
---

# FOSS Fall 2021 - Week 8, Thursday

----
## Topic: Repeatability, automation, and cloud computing

**FOSS Materials/Useful Links**


- [Instant Feedback (please complete before you leave class)](https://cyver.se/foss-feedback)
- [Course Homepage](https://learning.cyverse.org/projects/foss/en/latest/index.html)
- [Course Schedule](https://learning.cyverse.org/projects/foss/en/latest/schedule.html)

## Final Project Sheet

https://docs.google.com/spreadsheets/d/1OVVpRZe55C5b473qk7HB28J0i19scL_iSEqASdupQGM/edit?usp=sharing

Please fill this out **today**. We have added a column for which day you normally attend (Wednesday or Thursday), so if you've already filled it out, please go back and complete this column too.


## Links

#### Automation stuff

- https://rich-iannone.github.io/pointblank/
- https://rmarkdown.rstudio.com/
- https://quarto.org/
- https://bost.ocks.org/mike/make/
- https://snakemake.readthedocs.io/en/stable/tutorial/basics.html
- https://books.ropensci.org/targets/
- https://snakemake.readthedocs.io/en/stable/
    - See also this tutorial on CyVerse: https://learning.cyverse.org/projects/cyverse-cyverse-reproducbility-tutorial/en/latest/step4.html?highlight=snakemake
    - View a CyVerse webinar on Snakemake: https://www.youtube.com/watch?v=8Zlx6FvtHUk&t=22s

#### GitHub Actions

- https://docs.github.com/en/actions
- https://ryo-n7.github.io/2021-09-23-CanPL-GoogleDrive-GithubActions-Tutorial/
- https://emilyriederer.netlify.app/post/data-valid-lightweight/
- https://github.com/MCMaurer/gha_validation_demo

#### Software management

- https://brew.sh/
- https://chocolatey.org/
- https://rstudio.github.io/renv/index.html
- https://docs.conda.io/en/latest/

#### Cloud services

- https://mybinder.readthedocs.io/en/latest/index.html
- https://colab.research.google.com/
- https://www.gitpod.io/
- https://github.com/github/dev

#### Containers

- https://carpentries-incubator.github.io/docker-introduction/01-introduction/index.html
- https://carpentries-incubator.github.io/singularity-introduction/
- https://github.com/MCMaurer/my_custom_VICE_rstudio

---- 
## Discussion and notes


**General notes**

**Questions**

---

## Breakout Discussion questions & notes



### Q1: What are some tasks you have made more repeatable/automated?

**Room 1:** made reusable codes.

**Room 2:** 
Slowly learnin R to avoid manually changing things in excel and automate things. Setting up plots to repeat.

**Room 3:** mostly doing things manually but trying to learn R and improve R coding skills; (suggestions: to learn visualizations try this link: https://socviz.co/ use bioconductor vignettes; move away from excel; https://benjjneb.github.io/dada2/tutorial_1_8.html )

**Room 4:** generate synthetic data for burst detection in water distribution system, make the data consistent and repeatable. The algorithm for detecting the burst, like the parameters needs to be repeatable. Pipeline development, automation, should have same analysis across the project, better method for environment analysis for software systems.

**Room 5:** Data labelling, filling in missing data to enable scripts to run, feeding scripts into HPC.

**Room 6:** Still doing a lot of things by hand, automated some things in the lab but it took a lot of work.  Wants to go further.  Some visualizations are automated but data cleaning by hand. 


### Q2: What are some tasks you would like to make more automated/repeatable? What challenges are involved?


**Room 1:** 

**Room 2:** 

**Room 3:** 

**Room 4:** Adaptable pipe for different platform, systems and versions

**Room 5:** Automate latex template generation with previously used command, formats etc. Languages like IDL could produce incorrect results from command line statistical tests that are more complicated-- it would be better to code them up yourself using R or similar languages.

**Room 6:** Time is a challenge, making it work the first time is hard.  Time to debug your code. Generate a pipeline to automatically to analyze the data. Work on my own pipeline.  


### Q3: Are there any things you sort of "cross your fingers and hope it works"?

**Room 1:** Try new codes. 

**Room 2:** 
Using GIS data that might not have been cleaned well

**Room 3:** 

**Room 4:**

**Room 5:**

**Room 6:** Run smoothly after 7 years.  Hopes that code will work with new data without a lot of changes. Server managed by a different deparment and they install software it could change things. 


### Q4: Any experience with remote/cloud computing? Why? What platform? Any challenges?


**Room 1:** ALLofUS platform to do analyzing and coding on medical and clinical data. Every time when I logged out of the platform, I had to run all my code all over again.

**Room 2:** My lab uses a university server workgroup which is as close as we get to useing a cloud service, the benefits are everyone can acess the files whenever neede

**Room 3:** many of us use google docs, slides etc. ; challenges if internet connection is poor; advantages are similar graphica interface and the fact that everyone can see the updates immediately; use dropbox but there is a limit on storage without paying; how to access if someone leaves a position

**Room 4:** Try google CoLab, only heard HPC in the university. Matlab code takes time for a day, it would be better to learn HPC. University server, for projects, keeps records about the editing history

**Room 5:**
UA HPC services to extract large sets of data and for large data manipulation: much faster and saves time. Can feed multiple jobs into the resource manager at the same time-- highly efficient and saves your computer to do other things. 

**Room 6:** HPC for analysis of bioinformatics data, cyverse container camps. Slurm and cipres platform.  Anaconda for jupyter notebooks, and github.  All of computers backed up daily. HPC can be difficult to use. Always have to have a back-up plan on how to get your data off of a service if it goes away.  


### Q5: What are some perceived benefits to shifting more work to cloud/remote?


**Room 1:** Save computer space, easy to navigate, convenient for sharing and editing.

**Room 2:** 

**Room 3:** Benefits of sharing; backup;changes immediately availabe to everyone; everyone in group sees same interface

**Room 4:** More convenience, accessbility of other labs and members. People can coordinate with other more efficiently

**Room 5:** Running multiple scripts simultaneously, computing power, storage and memory. 

**Room 6:**  Being able to access your data from anywhere, more big and powerful than what you have available locally. Managed by people so you don't have to install software on your own. 



### Q6: What are some perceived costs/challenges to shifting more work to cloud/remote?

**Room 1:** Short sessions and quick timeouts on Cloud computing platforms are a challenge.

**Room 2:** 

**Room 3:** feeling exposed by sharing things that aren't quite ready; what to do if internet is not working; how to handle changes in staff; what to do if your email changes (institutional affiliation changes); challenging running multiple internet-dependent program simultaneously (computer slows down, programs (Zoom) freezes )

**Room 4:**

**Room 5:** Code needs to run with no bugs. If a script fails after running for days on the HPC and your code didn't contain print statements to track errors, it could be a disaster to follow your .out files. 

**Room 6:** Some things could have a cost associated. Need to have expertise to use some resources. There might be restrictions on space or data that you can utilize. 



### Homework Reminders

Homework link will be sent out by Friday!

----
