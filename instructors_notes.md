This file covers many of the discussion points from the workshop:

## 1. Download the data (10 min)

Explain how to get the data and what the archive contains. 

```
├── car-speeds.csv
├── plot1.png
├── plot2.png
├── rcode.R
└── results-final.docx
```

## 2. Investigate the contents of the files (10 min exercise, 5 min discussion)

- Do the files match the contents of the analysis?
- What are some of the problems you came across?

Allow 10 minutes for attendees to look at all the files and investigate.

_Pause for discussion_

Discussion points:

- can you trust the analysis?
- is the data included what generated the figures/analysis?
- how do you know what has been done?
- no explicit license
- no readme
- project structure needs to be created
- figures don't match
- numbers in analysis need to be checked
- results document is in a proprietary format
- no version control

## 3. Improve the repository (15 min, 5 min discussion)

- Separate code, data, results
- (optional) implement version control on the directory and track the changes you make
- add documentation
- (optional) convert analysis/documentation into a markdown (or Rmarkdown) document
- include metadata
- update the analysis
- anything else?

_After allowing time, get some attendees to share what they did_


# 4. Think about how you could make this analysis and data shareable (10-15 min discussion)

- what are some considerations for the code, analysis, and data?

The overarching consideration is who are other stakeholders/communities that need to be consulted before anything is shared
- does someone else needs to be part of the conversation - especially indigenous communities.

Code:
- who wrote the code -> IP considerations
  - insititution policies for IP ownership -> students and staff treated differently 
- is the code commercially sensitive?
- version control platforms e.g. github, bitbucket, gitlab etc.
  - should the repository be public or private?


Analysis:
- commercial sensitivity considerations
- making sure that communities are kept in the loop and updated

Data:

Three main principles ownership, where can the data be stored, and size.

- Who owns/controls the data - make sure that indigenous communities are involved up front!
- What geographical restrictions are there for where the data is physically stored?
  - does it need to remain in country?
    - institutional data storage
    - cloud based storage: dropbox, aws, onedrive, azure, catalyst, etc.- > **where will the data be physically hosted?**
- Size of data will determine what methods of data sharing will be appropriate
  - github might be appropriate for small scale e.g. < 100 MB
- Consult with institution librarians (if available)

