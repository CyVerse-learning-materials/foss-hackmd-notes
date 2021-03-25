# FOSS Spring-2021 Week 6, Wednesday

----
## Topic: Reproducibility Tour 1

**FOSS Materials/Useful links**


- Instant Feedback (please complete before you leave class):
    - [https://cyver.se/foss-feedback](https://cyver.se/foss-feedback)
- Course Homepage 
    - [https://learning.cyverse.org/projects/foss/en/latest/index.html](https://learning.cyverse.org/projects/foss/en/latest/index.html)
- Course Schedule 
    - [https://learning.cyverse.org/projects/foss/en/latest/getting_started/schedule.html](https://learning.cyverse.org/projects/foss/en/latest/getting_started/schedule.html)


**Section Links**

- Reproducibility Tour: [Tutorial](https://learning.cyverse.org/projects/cyverse-foss/en/latest/reproducible_science/intro.html)
- Atmosphere Cloud Computing: [Atmosphere](https://atmo.cyverse.org/application/images) (remember to shelve your instance before you log off)
- Atmosphere Guide [Learning Center](https://cyverse-atmosphere-guide.readthedocs-hosted.com/en/latest/)
- GitHub: [Github](https://github.com/)
- JetStream [JetStream Cloud](https://jetstream-cloud.org/)
- Slides on cloud computing [slides](https://de.cyverse.org/dl/d/AD2120F7-230B-48CA-8D1D-A70831C40D76/WILLIAMS_Jason_In-Nube_foss.pdf)
- SSH Atmosphere [learning center](https://cyverse-atmosphere-guide.readthedocs-hosted.com/en/latest/step3.html#connect-to-atmosphere-instance-using-ssh)
- Windows PuTTY download: [Download](https://the.earth.li/~sgtatham/putty/latest/w64/putty.exe)



---- 
### Discussion and Notes

**General Notes**

Questions for breakout discussion:

1. How do you define reproducible science?
2. How do [the given] definitions apply to your research/teaching?

Data management exercise 

1. Read through the tutorial with your group. What features from your data management plan apply to things you see in the tutorial (e.g. how you will organize your data, software tools, etc.)

**Troubleshooting:  What if I said 'no' to the SHA256 fingerprint question?**

1. Try running `ssh-keygen -R YourAtmoIPaddress`


*If that doesn't work...*

2. Try removing the host from the file `~/.ssh/known_hosts`

*If you can't find the line with the IP address...*

3. Remove the whole `known_hosts` file by running `rm ~/.ssh/known_hosts` or `sudo rm ~/.ssh/known_hosts`

---

**Breakout Notes**

Team A re-perform the original analysis and adapt it to new data;  being able to see if findings generalize;  reproducibility should be achievable to data analysis, but may be more difficult for data generation/collection

In terms of our research/teaching, generating reproducable pipelines is definitely important and of concern.  Teaching the importance of that is difficult.

Team B
* time efficient and allows for easy sharing of results to others and/or use work for their own analyses
* make date pre-processing to be automated and save yourself and others time down the line

Team C

1. How do you define reproducible science?
Reproducible science allows for research to build up and move science forward without having to take the time to work from the raw data. It takes away the barriers of not having access to certain resources or priveleges (that one may lose after leaving university) and wanting to reproduce the science later on.
3. How do [the given] definitions apply to your research/teaching?
Use the dataset from another study to enhance your study or apply methods or approaches in a different setting with confidence.



Team D
* Reproducible science should be that everyone, even across disciplines, can use the data/analysis/code/results for their own research. 
* We want our research to be reproducible across our discipline and others. 

Team E

* Reproducibility in science is the ability to regenerate the same results given the same input data, code, and software, and well-documented, standardized wet-lab methods. The lack of reproducibility calls into question the validity of inference.
* In our own teaching and research, before even drawing conclusions, we (try to) make sure that the results are reproducible by planning our methods in advance and subsequently documenting our process.

Team F 
* The ability to regenerate the results using the same data and analyses.
* We test deep learning models from github repositories and we also upload our own models and data to github so our data and code can be reproducible. 
* We generate visualizations and tables/stats from code stored/controlled in git repositories in github.
* All software archived in git repositories

Team G
    1. Something that others can do again - exactly
    2. setting up VM's so others can do exactly what we have done
        setting up VM's so students can cut & paste commands & get the same results
        using compute clusters with scripts
        providing example data & results
        


---

### Homework Reminders

- Go through the questions on the Intro to Reproducible Science tutorial: https://learning.cyverse.org/projects/cyverse-foss/en/latest/reproducible_science/intro.html
- Think about how you would make the workflow/tools you use in your domain reproducible (if not doing genomics as in the example)
- Find out what license(s) your institution recommends (or requires)for your code and research data?
- Think about your answers to the Data Management exercise above (as we'll start off with this next week in your team breakout)

----