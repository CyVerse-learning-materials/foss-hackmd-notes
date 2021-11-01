---
tags: foss-fall-21
---

# FOSS Fall 2021 - Week 7, Wednesday

----
## Topic: Interactive analyses 

**FOSS Materials/Useful Links**


- [Instant Feedback (please complete before you leave class)](https://cyver.se/foss-feedback)
- [Course Homepage](https://learning.cyverse.org/projects/foss/en/latest/index.html)
- [Course Schedule](https://learning.cyverse.org/projects/foss/en/latest/schedule.html)
- [Today's content](https://learning.cyverse.org/projects/foss/en/latest/05_version_control.html)

## Links

- [Reproducible Research in Computational Science](https://www.science.org/doi/10.1126/science.1213847)
- [Ten Simple Rules for Reproducible Computational Research](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003285)
- [Scientific progress despite irreproducibility: A seeming paradox
](https://www.pnas.org/content/115/11/2632)
- [Project Jupyter](https://jupyter.org/)
- [VICE guide](https://learning.cyverse.org/projects/vice/en/latest/)
    - [Jason's VICE Webinar](https://cyverse.org/VICEwebinar)
- [Create github access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)
- [Conda package manager](https://docs.conda.io/en/latest/)


---- 
## Discussion and notes


1. Reproducibility discussion. 


3. Use case example: Building a Github to Jupyter workflow using CyVerse. 



    **Steps**
    
    1. Clone a repository of Jupyter notebooks from GitHub 
       to a space on the CyVerse Data Store 
       
       - Demonstrate using mybinder.org 
       - Demonstrate using VICE
           -  Fork to a personal GH repository
               -  `git clone repository_url`
               -  We will try: https://github.com/genomics-education-alliance/leptin-mouse-rnaseq-docker
               -  `git clone https://github.com/JasonJWilliamsNY/leptin-mouse-rnaseq-docker.git` 
                   -  Be sure you use your own username for the clone if you would like to version control this repo ex. `git clone https://github.com/UserName/leptin-mouse-rnaseq-docker.git`
               -  `iinit # setup iCommands`
               -  `iput -rP # put copy of your cloned repo in the Data Store`
           -  Clone using webshell 
       
    2. Launch and edit notebooks using a VICE instance
        - VICE jupyter data science app: https://de.cyverse.org/apps/de/07a2d5b2-76e2-11eb-be5f-008cfa5ae621/launch?saved-launch-id=60054c75-0e80-4169-8a9b-51cba04f756d 


    3. Push notebooks back to your forked repository 
        - Create a GH access token                                                                    - "https://github.com/settings/tokens/new # use "cyverse_vice for Note; 7 days experationScopes: repo, write:packages, admin:org, admin:public_key, admin:repo_hook"
        - Configure git on the webshell instance 
        - Install Github CLI
            - See: https://github.com/cli/cli#installation
            - `conda install gh --channel conda-forge`
            - Cash credentials
            - See: https://docs.github.com/en/get-started/getting-started-with-git/caching-your-github-credentials-in-git
            - `gh auth login`
        - Push back to Github 





---


## Breakout Discussion questions & notes

1. How do you define reproducible science?

    After discussing on your own, review definitions: [Reproducibility vs. Replicability: A Brief History of a Confused Terminology](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5778115/)
    
    - Reproducibility: anyone can understand and replicate the process of the analysis
    - Transparency in your methods, code, data
    - Providing clear steps and tools to reproduce your work.
    - Reproducibility to me means creating a structure and methodology for a project to be easily retested and validated
    - Also add the data used in the paper
    - I can use your data and methods and get the same results
    - Documentation to reproduce the same analysis to get the same results
    - Replicability: reproducibility but with the exact same research question
    

2. How do these definitions apply to your research/teaching?





### Homework Reminders

Homework link will be sent out by Friday!

----
