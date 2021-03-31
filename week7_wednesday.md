# FOSS Spring-2021 Week 7, Wednesday

----
## Topic: Reproducibility Tour 2 - Containers

**FOSS Materials/Useful links**

- Instant Feedback (please complete before you leave class):
    - [https://cyver.se/foss-feedback](https://cyver.se/foss-feedback)
- Course Homepage 
    - [https://learning.cyverse.org/projects/foss/en/latest/index.html](https://learning.cyverse.org/projects/foss/en/latest/index.html)
- Course Schedule 
    - [https://learning.cyverse.org/projects/foss/en/latest/getting_started/schedule.html](https://learning.cyverse.org/projects/foss/en/latest/getting_started/schedule.html)
- Genomics Reproducbility Tutorial
    - [https://learning.cyverse.org/projects/cyverse-cyverse-reproducbility-tutorial/en/latest/index.html](https://learning.cyverse.org/projects/cyverse-cyverse-reproducbility-tutorial/en/latest/index.html)

***Capstone II Projects:***

Do the following on your team GitHub pages website:

1. Have each team member write a paragraph on tools or concepts learned through FOSS and how they might apply to their field of study. In this paragraph, please address the following questions:
    * Which tool could you apply right away and why?
    * What is your greatest barrier to these tools?
    * What tools would you wish we covered more in depth? 

2. Getting together as a team, which tool or concept do you feel is closest to implementable... could you would together as a team to develop a project on this?
    * Think about the [Reproducibility Tour](https://learning.cyverse.org/projects/cyverse-cyverse-reproducbility-tutorial/en/latest/index.html) as a guideline, but work together to align your team and individual goals.
    * Use GitHub pages to document your team's ideas

3. The journey is more important than the goal. We want your capstone projects to guide you toward your next steps after FOSS. 

**Section Links**

- Reproducibility Tour: [Tutorial](https://learning.cyverse.org/projects/cyverse-foss/en/latest/reproducible_science/intro.html)
- Atmosphere Cloud Computing: [Atmosphere](https://atmo.cyverse.org/application/images) (remember to shelve your instance before you log off)
- Introduction to [Containers](https://learning.cyverse.org/projects/cyverse-foss/en/latest/Containers/introtocontainers.html#)
- Atmosphere Guide [Learning Center](https://cyverse-atmosphere-guide.readthedocs-hosted.com/en/latest/)
- GitHub: [Github](https://github.com/)

---- 
### Discussion and notes

**General notes**

Discussion Questions for Breakout:

We've been using atmosphere, which is a virtual machine running on a cloud server. The following is a link to the difference between containers and virtual machines: [Containers vs. Virtual Machines](https://blog.netapp.com/blogs/containers-vs-vms/).

1. How might you use containers in your work? 
     
2. Do you think containers can help your teaching or research reproducibility?

---

**Breakout notes**

Team A:
- Project Planning Notes:
        - set up a pipeline for RNAseq that could be used by all of our group members
        - How will we do this? 
            - data management plan inclusion - agreed upon data input and output formats
            - sort out workflow
            - create HackMD site to outline pipeline flow (maybe do this on Github)
            - build container to link workflow
            - host the container somewhere accessible
- Container Discussion Questions:
    1. How might you use containers in your work?
         - virtual box in a class so everyone uses the same without downloading individual programs
         - portable code for use by multiple people on a single or shared project for standardized use
         - standardized code for routine analyses used in research lab settings
    2. Do you think containers can help your teaching or research reproducibility?
        - in teaching, no install issues to deal with in class, can go straight to the work
        - in fundamentals classes that focus on basic foundational info (like stats) you can use containers so the students don't have to focus on learning to code and can instead focus on learning the basics
        - Makes direct replication of research and workflows much simpler for the end-user, therefore more likely to happen

Team B:
- Project Planning Notes:
    - use some smaller example data do object detection
    - determine unique lettuce species from images
    - use docker containers for analyses
    - keep scripts in shared github repo, maybe the reproducibility-tour one
    - use CyVerse data store to share data, add team members as collaborators

- Container Discussion Questions:
    1. How might you use containers in your work?
        - run R/RStudio with dependencies already installed, perform analyses, and save outputs for sharing with collaborators.
        - use them to install dependencies for training Neural Networks on HPC.
    3. Do you think containers can help your teaching or research reproducibility?
        - Yes, can have needed apps for a lesson in a container so all learners can use without install/version issues
        - Yes, can assign docker container image a DOI

Team C:
- Project Planning Notes:
    - Create a docker container that links data and a jupyter notebook that can be accessed after a publication
- Container Discussion Questions:
    1. How might you use containers in your work?
            - ease of sharing files and code between collegues  
            - government agencies want software developed but don't want to give you the data. Containers are used to deliver sofware so that government agencies use them internally.
    3. Do you think containers can help your teaching or research reproducibility?
            - if packages are needed that require an older version of RStudio, for example, containers are helpful in making sure everyone has access to the same version and can run the necessary packages
            

Team D:
- Project Planning Notes:
    - Use the outline of the reproducability tour to create guidelines on how to handle my data for my project. This would include using tools like DSWizard, Command line, pushing to GitHub, and creating a GitHub Page. 
    - Ida may be the only on in our group who currently works with data. She is not here today, but she could provide details about her project and how we could make the capstone revolve around making her data FAIR
- Container Discussion Questions:
    1. How might you use containers in your work?
        - Instead of using GitHub to host source code and instructions for dependencies, use a docker container
    2. Do you think containers can help your teaching or research reproducibility?
        - Less time needs to be spent on configuring/setting up environment/dependencies onto remote/local machine
    
Team E:
- Project Planning Notes:
    - start here
    - Create a dummy pipeline using a small public dataset
        - e.g. for assembling a bacterial or phage genome pipeline could go from pulling dataset through assembly
- Container Discussion Questions:
    1. How might you use containers in your work?
        - A Docker container version of an R package that I've led the development of is available in VICE as the app `rstudio_neon_microbiome`
    3. Do you think containers can help your teaching or research reproducibility?

Team F:
- Project Planning Notes:
    * Containerization of cotton yield estimation with aerial imagery pipeline
- Container Discussion Questions:
    1. How might you use containers in your work?
        *  Deploying webserver, distribute for others to run, useful to teach short courses or tutorials
    3. Do you think containers can help your teaching or research reproducibility?
        * yes, for teaching R - one environment to serve them all.
        * people can (sometimes) treat docker images like a kitchen sink and dump all sorts of unorganized junk in it
        * I'm unclear how much it can support rouine low level reproducible research - a leaner solution may be needed (I don't know) 

Team G:
- Project Planning Notes:
    - We will be utilizing atomosphere to enable to students to use the programs for genomics research. 
        - How will we achieve this? 
            - The tool will be QIMME 
            - Analysis DADA 2 analysis of microbiomes
                - Taking DNA sequences are seeing what bacteria are represented
                    - Looking at ticks, we can determine what potential pathogenes exist in them
    - Travis: Scouting for exising QIMME on cyverse or determine whether we will need to begin from scratch.
    - Gabe: Look into how take a VM and mirror the VM on Docker. 
        - Week 7: 
            - Touching base with team on Friday to report progress and issues. 
        - Week 8:
            - 
        - Week 9: 
            - Meet Tuesday to confirm final capstone work



- Container Discussion Questions:
    1. How might you use containers in your work?
        2. To simulate a VM for a specific project or purpose. 
    3. Do you think containers can help your teaching or research reproducibility?
        4. Improves consistency of content, allowing for uniformed experiences and trouble shooting. 

---

### Homework Reminders

- Try Biocontainers tutorial
    - [Tutorial Link](https://learning.cyverse.org/projects/cyverse-cyverse-reproducbility-tutorial/en/latest/step3.html)
----