# FOSS Spring-2021 Week 8, Wednesday

----
## Topic: Reproducibility tour....

**FOSS Materials/Useful links**


- Instant Feedback (please complete before you leave class):
    - [https://cyver.se/foss-feedback](https://cyver.se/foss-feedback)
- Course Homepage 
    - [https://learning.cyverse.org/projects/foss/en/latest/index.html](https://learning.cyverse.org/projects/foss/en/latest/index.html)
- Course Schedule 
    - [https://learning.cyverse.org/projects/foss/en/latest/getting_started/schedule.html](https://learning.cyverse.org/projects/foss/en/latest/getting_started/schedule.html)

- Reproducibility tour
    - [https://learning.cyverse.org/projects/cyverse-cyverse-reproducbility-tutorial/en/latest/index.html](https://learning.cyverse.org/projects/cyverse-cyverse-reproducbility-tutorial/en/latest/index.html)

---- 
### Discussion and notes

**General notes**

In opening breakouts, do your best as a team to try and answer the follwing questions (all related to the tutorial)


1. What is the point of starting a GitHub repository at the start of the project? What will you be doing with this? 

2. What differences can you name between
 
   a. installing Conda
   
   b. using Conda to install other tools? 

3. What is the difference between using a tool installed with Conda vs. using a tool in a Docker container? 

4. What is the point of copying data to the datastore (end of the section "Computer and project setup with Github, Conda, and the Data Store")



---

**Breakout notes**

**Team A**


1. What is the point of starting a GitHub repository at the start of the project? What will you be doing with this?
- helps keep 'stuff' in one place
- share code with teammates/group (maintain continuity)
- outline shared work
- version control
- we will use this for collaborative projects/workflows

2. What differences can you name between

a. installing Conda
-management system only, can't run anything
b. using Conda to install other tools?
Conda is a package managment system.  It helps you manage workflows etc, but doesnt' actually do the work you want to do.

3. What is the difference between using a tool installed with Conda vs. using a tool in a Docker container?
- docker easier to share and comes with dependancies
- conda you have to add dependancies
- conda installs on your OS where docker runs within container


4. What is the point of copying data to the datastore (end of the section “Computer and project setup with Github, Conda, and the Data Store”)
- data sharing and workflow sharing at end



**Team B**

1. What is the point of starting a GitHub repository at the start of the project? What will you be doing with this? 

* track changes and updates for projects
* set up team and collaborators
* work together simultaneously
* increase time efficiency by eradicating the need to copy the codes on multiple devices

2. What differences can you name between
 
   a. installing Conda
   
   b. using Conda to install other tools? 
   
   * by installing conda we gain the ability to install other packages
   * have on a local computer
   * reduce conflicts between different packages installed 
   * install multiple packages and depencies needed
   
3. What is the difference between using a tool installed with Conda vs. using a tool in a Docker container? 
    
    * In docker containers we have more power on networking aspects of the system and we have a more isolated environment and we can manipulate the guest operating system more freely when we are using different tools. Conda is a virtual environment whereas docker containers are more like a virtual operating system. 

4. What is the point of copying data to the datastore (end of the section "Computer and project setup with Github, Conda, and the Data Store")

* reproducibility, making it possible for other people to repeat our experiments
* back up work, share with team, assign metadata

**Team C**
    
1. What is the point of starting a GitHub repository at the start of the project? What will you be doing with this?   
> keep track of changes, having and building clear documentation of what you work does (building it as you go), enables collaboration through tracking and push pulling

2. What differences can you name between  
   a. installing Conda
> this is a tool that helps you to install things

   b. using Conda to install other tools?   
> equivalent (? but better than) to pip install, let's you install pacakges and dependencies for python and other tools


3. What is the difference between using a tool installed with Conda vs. using a tool in a Docker container?   
> **_Question:_** when we use docker, are we just talking to a virtual computer that hosts the programs instead of downloading it onto our own computer? We think this is the difference but we're all still a bit confused on what docker is "doing"

4. What is the point of copying data to the datastore (end of the section "Computer and project setup with Github, Conda, and the Data Store")  
> Github can't host large files but the datastore can  
> Jason says scratch returns to system and gets erased, datastore is persistent

**Team D**
1. What is the point of starting a GitHub repository at the start of the project? What will you be doing with this? 

    * Using GitHub at the start of a project allows the team to efficiently upload and share code/files while keeping track of a history of commits and contributions by each team member.

2. What differences can you name between
 
   a. installing Conda:
       
      * Conda is installed onto the local computer. 
   
   b. using Conda to install other tools? 
       
      * Conda helps install mangement systems as well as different packages which you can then use on the local machine you installed Conda on. 

3. What is the difference between using a tool installed with Conda vs. using a tool in a Docker container? 

    * Both tools run software packages. Docker comes with the dependencies already within the package, and is easier to share the application. Conda installs specified software that the user tells Conda to download. This doesn't necessarily mean that it is an application. This is unlike Docker which is an application and contains all the necessary information to run the application. 

4. What is the point of copying data to the datastore (end of the section "Computer and project setup with Github, Conda, and the Data Store")

    * If local machine is gets corrupted, data is safeley stored externally. 
    * With a datastore you may also run computational analysis on the data provided.
    * Other collaborators can use the data when stored on the Datastore. 
    * Data is closer to being FAIR.


**Team E**
1. What is the point of starting a GitHub repository at the start of the project? What will you be doing with this?
    - Have a record of all you and your collaborators have done
    - The point of GitHub, which is to collaborate with version control, allowing you to merge different versions of your code and retrieve old versions of your code
    - 


2. What differences can you name between

    a. installing Conda

    b. using Conda to install other tools?

    Conda is installed in your computer, whereas when you use conda to install other tools those will be in the conda environment of your choice.


3. What is the difference between using a tool installed with Conda vs. using a tool in a Docker container?

    Conda allows for more modular uses of tools. With Conda you still will have to install some of the dependencies, or make sure they are in the same environment as the tool you will use. Whereas a Docker container will contain everything you need for the intended task, and nothing more.

4. What is the point of copying data to the datastore (end of the section “Computer and project setup with Github, Conda, and the Data Store”)
    



**Team F**

1. What is the point of starting a GitHub repository at the start of the project? What will you be doing with this? 
Storing/versioning code and changes over time, including attribution.  Backup.   Project website.  Invite collaborators.  Get feedback/issues from the public. 

2. What differences can you name between
 
   a. installing Conda

Installed via an installer, i.e. not a package.
   
   b. using Conda to install other tools? 
  
These are packages managed by conda in a specific environment, which can be used to have multiple versions of packages on the same computer but isolated from each other.  

3. What is the difference between using a tool installed with Conda vs. using a tool in a Docker container? 

The tool is running in the docker container and has access to those resources that the docker container exposes, vs with conda, the tool has access to the computer directly. How you launch the tool is a different sequence, i.e. conda activate, then run vs docker run.  

4. What is the point of copying data to the datastore (end of the section "Computer and project setup with Github, Conda, and the Data Store")

So you can use (mount) the data easily and efficiently to containers and virtual machines. Allow others to use data and results.  

**Team G**
1. What is the point of starting a GitHub repository at the start of the project? What will you be doing with this?
    a. To establish a central repository for all work amd ensure that work can be coordinated effectively without wasting time and energy. 
    b. Creating a repository for our team to work on our capstone. 


2. What differences can you name between
 
   a. installing Conda - 
       Conda is a tool [that lets you efficiently install other tools]
       You can't use conda to install conda
   
   b. using Conda to install other tools? 
       Conda can be used to install & maintain (update) the tools/packages.

3. What is the difference between using a tool installed with Conda vs. using a tool in a Docker container? 
    a. Conda installs the tools natively in your operating system/vm, whereas a tool in a docker container exist only within the container. For tools to be used in a container, they must be installed everytime the container is first booted up. 

4. What is the point of copying data to the datastore (end of the section "Computer and project setup with Github, Conda, and the Data Store")
    a.Allows for the data to be used and shared within Cyverse.  



---

### Homework Reminders

----