# AutoRABIT  

[AutoRABIT](https://www.autorabit.com/) feature migration connector helps in identifying the typical nCino object relationship and allows users/release mangers to migrate data and matadate 10x faster.

## Getting Started

The nCINO documentation for users is located in the [AutoRABIT/docs](https://docs.autorabit.com/).

To get set up and running quickly:

 - Work through the [Tutorial](http://course-catalog.teachery.co/lessons/devops-academy)

Once you are familiar with the tutorial, you’re ready to move on. To start migrating nCino record based configurations, see the AutoRABIT docs.

To better understand how AutoRABIT works with the ncino record based migration see the reference materials.

Getting Help
------------

Check the [AutoRABIT FAQ](http://course-catalog.teachery.co/lessons/devops-academy) and read through the [Top 10 questions on nCino Feature Migration](http://course-catalog.teachery.co/lessons/devops-academy).


## Prerequisites

 - nCino installed salesforce orgs
 - AutoRABIT enterprise licence account

## Description of Files and Directories

### A typical top-level directory layout

    .
    ├── config                   # Compiled files (alternatively `dist`)
    ├── dataset                    # Documentation files (alternatively `doc`)
    ├── LICENSE
    └── README.md

### Configuration files
.

    ├── ...
    ├── config                    # Test files (alternatively `spec` or `tests`)
    │   ├── manifest.yaml         # Load and stress tests
    │   ├── project-def.json      # End-to-end, integration tests (alternatively `e2e`)
    └── ...

### Data files
.

    ├── ...
    ├── dataset                          # Test files (alternatively
    │   ├── Features                     # Load and stress tests
    │          ├── .store      			 # End-to-end,    
	│          ├── data      			 # End-to-end,
	│          ├── filters      		 # End-to-end,    
	│          ├── objectsets.json       # End-to-end, 
    │          ├── Version.json     	 # End-to-end,    
	│          ├── autorabit.json        # End-to-end,
	│          ├── buckets.json      	 # End-to-end,	
	│          ├── userids.json      	 # End-to-end,     
    └── ...



## License
[MIT](https://choosealicense.com/licenses/mit/)