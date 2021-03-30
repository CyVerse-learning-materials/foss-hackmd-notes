# FOSS Spring-2021 Week 7, Tuesday

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
3. How can you save/back-up your work in either a VM or container?

---

**Breakout notes**

Team 1

*Tools or concepts learned through FOSS*
- Data management plans

- Start from the beginning of a project. Influences way data and experiments are approached. Not just for applying funding
- Look to see if any other GitHub pages or software has addressed doing this
- Explore more what GitHub can do

*Project ideas*

- DMP template for research projects
- template on GitHub that includes detailed plans for DM.
- including file name convention
- find way of linking to archived or past data

### How might you use containers in your work?
To create and share repeatable and reproducible workflows. 
### Do you think containers can help your teaching or research reproducibility?
Yes, because dependencies are included, allowing exactly the same workflow to be used.  Particularly on different machines

### How can you save/back-up your work in either a VM or container?
Put a link to container on Github, some things will be lost when VM shelved? Not sure of details of this.  Modifying container to deal with your data or situation?

# Team 2
- Implemetable tools or concept as a team
    -Data Stewardship Wizard: To create an organized roadmap for our projects (DMP)
    -GitHub Pages: To create/host website about ourselves, ongoing projects or            organization
    -CyVerse Datastore: To securely store data, where each member of the team can have aceess to.

Team 3
- Possibly work on GitHub (gain experience)
- Use NEON (National Ecological Observatory Network) data to get a starting dataset and then use Cyverse to do some of the analysis
    - Use Cyverse to launch virtual machine and access jupyter notebook or terminal 
    - Maybe create a small piece of code that gathers the data and graphs it (some basic stuff)
    - Code language we want to use: R and python
    - Data we are using: Biology data
    - We can try and containerize the code to be easily deployed (depends on time)

How might you use containers in your work?

Do you think containers can help your teaching or research reproducibility? So we can focus in on teaching and not on IT mateirals.   LIke above alows us to focus onwhat are looking at.  

How can you save/back-up your work in either a VM or container?

- Through github
Team 4

Team 5
* Tools for individuals:
    * Kayla: GitHub
    * Bob: Snakemake, DataStore/CyVerse tools, tools we are about to learn
    * Carla: GitHub, potentially
        * Concerns about private vs public repo permissions, licenses, data availability
    * Lisa: GitHub, data management (planning and execution)
* Tools/Ideas for Capstone II:
    * We had previously discussed using Snakemake to build a workflow to process remotely sensed data (Landsat scenes?) 



---

### Homework Reminders

- Try Biocontainers tutorial
    - [Tutorial Link](https://learning.cyverse.org/projects/cyverse-cyverse-reproducbility-tutorial/en/latest/step3.html)