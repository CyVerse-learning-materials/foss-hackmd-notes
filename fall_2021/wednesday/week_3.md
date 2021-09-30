---
tags: foss-fall-21
---

# FOSS Fall 2021 - Week 3, Wednesday

----
## Topic: Data Management

**FOSS Materials/Useful links**


- Instant Feedback (please complete before you leave class):
    - [https://cyver.se/foss-feedback](https://cyver.se/foss-feedback)
- Course Homepage 
    - [https://learning.cyverse.org/projects/foss/en/latest/index.html](https://learning.cyverse.org/projects/foss/en/latest/index.html)
- Course Schedule 
    - [https://learning.cyverse.org/projects/foss/en/latest/schedule.html](https://learning.cyverse.org/projects/foss/en/latest/schedule.html)

- Today's content
    - [https://learning.cyverse.org/projects/foss/en/latest/02_project_management.html](https://learning.cyverse.org/projects/foss/en/latest/02_project_management.html)

**Links from today**

- https://datadryad.org/stash
- https://fairsharing.org/
- https://hackmd.io/mC5d966cQ9m33j1cv8CKmQ
- [using Cyberduck](https://learning.cyverse.org/projects/data_store_guide/en/latest/step1.html)
- Data management in the Discovery Environment: https://learning.cyverse.org/projects/discovery-environment-guide/en/latest/step2.html
- https://learning.cyverse.org/projects/discovery-environment-guide/en/latest/step6.html


---- 
## Discussion and notes

**General notes**

re: threads about metadata
- Examples Ontologies from the life sciences: http://www.obofoundry.org/
- Linked Open Data Cloud https://lod-cloud.net/
- Schema https://schema.org/
- 

**Questions**

---

## Breakout Discussion questions & notes



### Q1: What are the 2-3 data types you work with the most?

**Room 1:** 

- MRI scans (4D)
- Landsat imagery
- time series
- Remote Sensing
- RNA DNA seq

**Room 2:** 
- images. spatial analysis
- tabular data. some single-digit and some in millions re frequency
- images of specimens/organisms. varying quality. tens of thousands. may be from museum staff
- manually filled out spreadsheets, sequence data specialized files. JSON files for metadata.

**Room 3:** 
- netCDF data in 3-4 dimensions covering large areas of the globe over a long period of time
- csv data from a sensor using multiple wavelengths to take measurements at a fixed point
- tabular format for biological data
- Photos from Drone Phenotyping

**Room 4:** 
- real-time data
- spatial analysis, global and local scale
- sequence data
- environmental metadata

### Q2: What is the scale of your data? Volume, velocity, variety, and veracity.

**Room 1:** 
- volume:
    - drone data: MB -> GB -> TB -> cloud-optimize -> KB
- velocity:
- variety:
- veracity:

**Room 2:** 
- volume:
    - multiple GBs.
    - TBs from specialized machine.
    - mailed hard drives
- velocity
    - snail mail
    - quarterly data releases
- variety:
    - from different people
- veracity:
    - validation for metadata


**Room 3:** 
- volume:
    - MB
    - GB if I'm using daily data over a long period of time
- velocity: 
    - usually the data does not come out quickly
    - data must be manually entered from handwritten datasheets
- variety:
    - Sometimes I work with huge data sets on a  climatological scale and sometimes I work with smaller point source data.
- veracity: 
    - Sometimes there is no ground truth data set to validate my data against. 
    - Usually it depends on the situation.  If there are issues when collecting data then we don't use that data in our analysis.

**Room 4:** 




### Q3: What is your storage/backup strategy?

**Room 1:** 
- external hard-drives in a drawer
- GoogleDrive


**Room 2:** 
- HPC filesystem and tiered storage, e.g. tape backup
- google drive
- laptop
- globus / scp transfer
- dropbox
- hard drives
- Box

**Room 3:** 
- shared folder on my department's server 
- OneDrive
- Google Drive
- hard drive w cloud backup
- [Breedbase](https://breedbase.org/)

**Room 4:**
- Google Drive, Wasabi/cloud storage, dropbox, HPC, external hard drive


### Q4: How do you verify the integrity of your data?

**Room 1:** 
- I don't! Okay, I do, but only with file transfer checksums

**Room 2:** 
- sha256 hashes
- json schema and python tools
- machine has built-in data checks
- PCAs / outlier analysis
- repeating measurements to evaluate variability

**Room 3:** 
- multiple people collect ecological plant data out in the field, so observer bias must be accounted for
- sha256 hashes
- minimum, maximum, boxplot to look for typos

**Room 4:** 
- using data standards
- 


### Q5: How do you search your data?

**Room 1:** 
- indexing
- project folder
- unique file names
- elastic search

**Room 2:** 
- python to search data
- jq for json, grep, find, ag.
- R libraries
- web interface search box

**Room 3:** 
- Folders on computer
- R, usually dplyr
- idl when looking for specific values
- ncdump when trying to get a more broad overview of a netCDF file
- Wizard tool in Breedbase (Database)

**Room 4:** 
 - indexing within python, R, etc. 

### Q6: How do you share and get credit for your data? Or how do you plan to in the future?

**Room 1:** 
- README.txt 
- zenodo.org
- datacite through CyVerse
- google drive
- github

**Room 2:** 
- deposit in dryad or other repo
- companion publication
- Journal of Open Source Software (JOSS)
- github
- dryad accepts software scripts
- https://citation-file-format.github.io/-


**Room 3:** 
-GitHub
-figshare
-ftp server
-SRA (NCBI)
-Departmental Server
-sharing physical hard drive with research group members



**Room 4:** 
- deposit in repository
- github

### Homework Reminders

Homework link will be sent out by Friday!

----
