# Tidy projects

This repository is a workshop/tutorial which has been deisgned to illustrate (and provide the opportunity to pratice) some 
of the principles covered in the papers:

 - **Good enough practices in scientific computing**:
    <BR>
    Wilson G, Bryan J, Cranston K, Kitzes J, Nederbragt L, Teal TK.  PLoS Comput Biol. 2017 Jun 22;13(6):e1005510.<BR> 
    doi: [10.1371/journal.pcbi.1005510](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510) 
 - **Ten Simple Rules for Reproducible Computational Research**
    <BR>
    Sandve GK, Nekrutenko A, Taylor J, Hovig E. PLoS Comput Biol. 2013 Oct;9(10):e1003285. 
    <BR>
    doi: [10.1371/journal.pcbi.1003285](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003285)

A presentation which works through some of these concepts is included in this repository: [PDF version](https://github.com/mikblack/resbaz-tidy-projects/raw/main/slides/resbaz-good-practice-slides.pdf)

Workshop attendees play the part of "new research group members", who receive a zip file from a former project/lab team member, and are needing to use this information to start working in their new role.

The zip file contains:

- data
- an R script for loading the data and making some graphs
- results derived from using the script
- a Word document containing some kind of report/commentary 

Your task is to:

### 1. Download the data file (5 min exercise)


**Data download link:** [`my-project-final.zip`](https://github.com/mikblack/resbaz-tidy-projects/raw/main/my-project-final.zip)

Two options:

(a) Use the command line to download and extract the data
```bash
# download the file on the commandline
wget https://github.com/mikblack/resbaz-tidy-projects/raw/main/my-project-final.zip

# extract the tar archive
unzip my-project-final.zip
cd my-project-final/
```

(b) Right click (or command-click on Mac) and download the file, and then extract the files into a folder called `my-project-final`.

### 2. Investigate the contents of the files (10 min exercise, 5 min discussion)
   
- Do the files match the contents of the analysis?
- What are some of the problems you came across?

_Pause for discussion_


### 3. Improve the repository (15 min exercise, 5 min discussion)
   
- (optional) implement version control on the directory and track the changes you make
- separate code, data, results
- add documentation
- (optional) convert analysis/documentation into a markdown (or Rmarkdown) document
- update the analysis
- anything else?

### 4. Think about how you could make this analysis and data shareable (10-15 min discussion)
   
- what are some considerations for the code, analysis, and data?

_Pause for discussion_

### 5. (optional) Apply the concepts of tidy projects to one of your existing projects    

Have a go at tidying up one of your existing projects.
