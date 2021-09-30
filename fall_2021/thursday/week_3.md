---
tags: foss-fall-21
---

# FOSS Fall 2021 - Week 3, Thursday

----
## Topic: Data Management

**FOSS Materials/Useful Links**


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
- [using Cyberduck](https://learning.cyverse.org/projects/data_store_guide/en/latest/step1.html)
- Data management in the Discovery Environment: https://learning.cyverse.org/projects/discovery-environment-guide/en/latest/step2.html
- https://learning.cyverse.org/projects/discovery-environment-guide/en/latest/step6.html


---- 
## Discussion and notes

**General notes**


**Questions**

---

## Breakout Discussion questions & notes



### Q1: What are the 2-3 data types you work with the most?

**Room 1:** 
- stable isotope analysis (small datasets)
- synthetic data (matlab)
- time series simulation models

**Room 2:** phenotypic data 
uses mainly excel

Data in .csv files, oberservational and genomic data, most analyese can be done on regular computer
Kbs-Mbs in file sizes, can run on a computer


**Room 3:** 
A lot of coordinate data, text, and geospatial data. | Sequencing data x 2 | Tabular data | Tabular data, unstructured text | image data. 

**Room 4:** reaction time data from experiments, geospatial data (big file size), tabular data from geospatial, image data that is distributed to statisticians and then returned, deidentified data, observation studies of animals - behavioral and tissue data; protein amount; occassionally send off tissues & metabolic data-which is large (use excel), genome sequencing and RNA sequencing (fastq files) - 80GB in one study (wow!); 


**Room 5:**
Data types: 
- Outcome data: ranges from ~50obs to 2 million. Often stored in simple relational databases (relatively low number of tables, all structured data)
- Clinical data: Relational database tables, n=1 million; miltimodal data inputs - laboratory, diagnostic reports, vitals, meds, procedures. Data can be structured, some semi structured, unstructured
- Household survey datasets in tabular format. Geospatial gridded environmental and socio-economic datasets, vector datasets of roads, buildings etc.
- Data collected in field with soil details - not huge volume but detailed and sensitive.
- Experimental data, usually in csv files. Also worked with survey datasets, socioeconomic, dietary datasets too.

data verification: 
- mostly via plots 

searching Data: 
- relying on file structure for finding files 
- data dictionaries 
- innate commands within SAS/STATA/R/SPSS 
- attr vs var/val labels on master data file prior to subsetting within the statistical management software up front to ease data searching later

sharing data: 
- very difficult: HIPAA data vs other expensive to collect; don't want to share. 
- perhaps post pub can publish a de-identified, subsetted dataset to encourage reproducibility/transparency?

### Q2: What is the scale of your data? Volume, velocity, variety, and veracity.

**Room 1:** 
- volume
    - KB to GB 
- velocity
- variety 
- veracity

**Room 2:**
- volume
    - KB to GB
- velocity
    - periodic data streams, tidalwaves of data
- variety 
    - time series data. velocity is on daily basis
    - different types depending on the project
- veracity
    - really careful version control for provenance and access
    - there are checks in place to monitor files
    - relativly low 
filtering in excel



**Room 3:** 
Variable, tabular data tends to be smaller, raster data can be large, changes frequently, veracity is good, variety can be widespread but everything has a geospatial compnonent | volume is variable, velocity - comes once and then she works with it. variety and veracity can vary. Microscopic images | volume - gigabyte, 1 table per experiement, veracity - was collected by someone else. | large amount of data, velocity is quickly, gigabyte to terabytes, need more bodies to analyze it. | pretty small, comes consistently, cvs, access database, veracity - just me.  

**Room 4:** some small and some big in volume; big to huge for image data; velocity is sometimes very fast and sometimes very slow; error files have to be reviewed in addition to the data;


**Room 5:**
Some small and some larger datasets, smaller tabular datasets up to global gridded files over a few years

### Q3: What is your storage/backup strategy?

**Room 1:** 
- keep backups with time machine

**Room 2:** 
- pay for service to mirror my machines, it is continuous when I am using them
- box.com and google drive


**Room 3:** 
Cyverse, discovery environment. Saved to disk | store data on a server that is backed up every 24 hours | cache server daily, mirror, github and cyverse for code. | backed up on hard drives, stored on jgi. | server backed daily, access database also backed up daily for cleaned data. also on hard drive. 

**Room 4:** 
cyverse is used as a backup; download it twice to different computers (to make sure that downloaded data is complete and intact); sometimes on galaxy; college of pharmacy work group that uploads to server, personal computers & usb personally; due to IRB must store only to box . . . not legally allowed to store elsewhere; trying to develop a plan for backup; want to develop policy regarding backup; right now individual computers/harddrive - hope to use Cyverse; want to collect for long-term; looking for a temporary place too - transition between raw data and next use of data; 

**Room 5:**
- Dropbox, box, locally, storage on a server with a manager, github with datasets and models

### Q4: How do you verify the integrity of your data?

**Room 1:** 
- medical data, 

**Room 2:** 
- checks in place during data collection, and separate the raw data out
using statistical modelling
interim protocols to make sure the data makes sense
ability to check variables based on value

**Room 3:** 
geospatial can map it, it can be apparent when something is off | check files (md5) to see if they have lost data | Compare downloads to the original date. 

**Room 4:** 
Use Python command to confirm data stays intact; script will tell if the data downloaded fails; file counts, row counts, if data can be easily visualized - that can show gaps of missing data, 

**Room 5:**
Plotting outliers, visual checks, reading papers that conduct sensitivity analysis between different geospatial datasets. 

### Q5: How do you search your data?

**Room 1:** 
- box
- descriptive file names

**Room 2:** 
- standardized file nameing strategy using system search function
- memory game
- i use structured data sets with proper filing naming and dates 
- correlate date with files
- file name, storage location, 

**Room 3:** 
public data, download as a csv, getting in sql. | no the sample numbers and can download them.  have it on his computer and organizes it into files. x2 |  in raw data database & access database. | software that looks for data (datawatch.api) to trigger analyses. 

**Room 4:** 
save data by project - all data from one project goes in one folder; put year and month underscore title of project; file names important

**Room 5:**
Key fields to search and pair down datasets. Labelling of key variables for easier selection.

### Q6: How do you share and get credit for your data? Or how do you plan to in the future?

**Room 1:** 


**Room 2:** 
- in many cases I don't, goes to GenBank
- shared drives, sharing physical hard drives 
- sharing depends on data, some over email, 
- google drive and university archival system


**Room 3:** 
wants to use cyverse more and plans to reach out | uploading to jgi | Publishing the data online - NCBI , Zenodo | Dryad - data repository, code on eScholaship, most recent code on Github. | can issue DOI, preprints, bioarchive, etc. | cyverse can also provide DOI's, metadata, etc.

**Room 4:** 


**Room 5:**
Challenging to share data and remove identifiable information. Some projects like to publish from their dataset before sharing. 

### Homework Reminders

Homework link will be sent out by Friday!

----
