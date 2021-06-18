
# Working with Data for REU Students
## A eight week workshop presented by Liz Dobbins, NGA  LTER

This eight week workshop will introduce undergraduate students to current best practices regarding reproducible scientific research and data. The first four weeks will focus on data at different stages of a research project, and how data might live on after the original project is complete. The next four weeks will cover basic tools that enable open science. This workshop is meant to be an introduction to topics students will confront if they continue as a graduate student or scientist. Each lesson will include real-world examples and time for interactive practice.

## Topic Overview

### Week 1: Reproducible Research and the Data Lifecycle
This lesson will explain the motivation behind thinking about data as its own thing, regardless of scientific discipline or results. This is the set-up for the rest of the lessons.
* What is reproducible research?
  * Why is it important?
* Description of the research data lifecycle (collection, preservation, publication, etc)
* Intro to best practices (scripting, metadata, preferred data formats, standards)
  * Archiving your own data so it will live on

(Introduce the data to download for the next lesson)

### Week 2: Tidy Data and Spreadsheet Best Practices
Much of a scientist’s work is data wrangling - the process of collecting and organizing data so that analysis can be done. Spreadsheets like Excel are handy for this. And using best practices at this stage will make script-based analysis easier later on.  
Will draw heavily from https://datacarpentry.org/spreadsheet-ecology-lesson/
* What are the basic principles of data organization?
* How do people and computers work with data differently?
* Interactive practice cleaning a messy dataset
* Exporting data as CSV files

### Week 3: Metadata - Making Data Understandable
A machine readable, tidy data file doesn’t leave room for lots of kinds of information about the data - like notes on techniques and quality control. This type of information goes into a separate file called metadata. Data isn’t complete without its metadata.
* What information goes into metadata?
* What to look for in other people’s metadata (tricky bits)
* Metadata standards (machine operable)
* FAIR principles as a goal for the future

(End with an assignment to find a source of relevant data)

### Week 4: Data Archives and other Sources of Data
You’ve had a few weeks to get started on your summer research project. Were you able to find data that was relevant to your project?   https://practicaldatamanagement.wordpress.com/2019/08/10/of-time-series-and-ticks/
* Students give 2-3 minute summaries of what they found
  * Formats you saw, metadata standards that were used
* Proper credits for collaborators and people who gave you data (provenance)
* If time: review of common data archives for ecology and oceanography

(Introduce the bash tools that need to be downloaded and installed for the next lesson)

### Week 5: Beyond the GUI
We interact with our Windows, Mac and Linux PCs via a Graphical User Interface (GUI). But data wrangling can be done more efficiently if we are familiar with the command line interface available via the bash shell. Commands we cover will be needed for the git lesson.  
Will draw heavily from http://swcarpentry.github.io/shell-novice/
* Introducing the bash shell
* Interactive working with files and directories
* Brief overview of other things you might like to try on your own

(Introduce the git stuff that needs to be downloaded for the next lesson)

### Week 6: Version Control with git
Version control systems like git are often associated with programming projects. However, version control tracks changes in any type of file. Being able to track changes is essential in reproducible research.  
Will draw heavily from http://swcarpentry.github.io/git-novice/
* What is version control?
* How can version control help with open science? (evolving requirements)
* Start a git repository on your local machine and practice tracking files

### Week 7: Sharing and Collaborating using GitHub
Once we have our files in git, we can share them with others via a remote server. GitHub is a popular service that houses these remote repositories. That makes collaboration with colleagues - even far away ones - possible.  
Will draw heavily from http://swcarpentry.github.io/git-novice/
* Starting your own GitHub account
* Copying your local repository to a GitHub repository
* Collaborating with others via GitHub
* What sorts of science projects have work on GitHub that you can leverage?
* How do you clone or fork those projects?

(Ask for topics students would like more detail on during the last week)

### Week 8: Wrap-up, Including an Opinionated Guide to Programming Best Practices
Liz has lots of opinions on good programming practices, and she’d like to share. But that won’t take a whole hour. So there will be plenty of time to cover questions on previous topics.
* Making code readable (reproducibility, again)
* Defensive programming and debugging
* How have these topics applied to your work?
* Student’s choice

## Instructor information: 
Liz Dobbins has been working with oceanographic data for more than 30 years in both academia and the private sector. She has collected data at sea, processed sensor data, mapped assets, utilized numerical models, and used open-source Python tools to ingest data into a public-facing data portal. She is a certified Carpentries instructor and is eager to talk about best practices regarding scientific computing.
