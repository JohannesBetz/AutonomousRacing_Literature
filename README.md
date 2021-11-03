# Autonomous Literature Overview

This repository contains an excel document and a bibtex file that includes all the literature, research papers and publications in the field of autonomous racing. Although the term of autonomous racing can be referred to different applications (e.g. drone racing) we are focusing in literature overview only on research from the field of autonomous racing. This list does not claim to be complete, we are happy to receive feedback from the community about missing papers. This list will be updated a few times a year to include new papers that were recently published.

Last Update: 02.11.2021

# References
The collected paper in this repository were used to create the Paper "Autonomous Vehicles on the Edge: A survey on autonomous racing". If you find the information in this repository we would be happy if you can cite the following paper.

* J. Betz, H. Zheng, A. Liniger, U. Rosolia, [(PDF)](https://www.researchgate.net/)

```
   @inproceedings{Betz2022,

   }
```

# Structure
The excel file currently includes 234 publications. We structured the excel file the following

1. Overview
2. Perception
   1. Localization
   2. Object Detection
3. Planning
   1. Global Planning
   2. Local Planning
4. Control
5. End-To-End Approaches
6. Additional Racing Applications
   1. Software Stacks
   2. Simulation
   3. Modelling

# Excel Document
This repository includes an excel document called "AutonomousRacing_Literature.xlsx". This file contains all the papers that are related to autonomous racing. We provided additional columns that gives interested readers the possibility to search for specific areas. You can filter order with the following information:
* Year
* Full Name of First Author
* Section: High level section we ordered the paper to
* Subsection: Subsection in the according high level section field
* Topic: General High Level the topic is can be assigned to
* Method: Main method that is used in the paper
* Real car tested: Was the algorithms (code) developed in the paper tested on a real vehicle (Sports car, Racecar, Roborace, Indy Autonomous vehicle) - yes/no
* Small car tested: Was the algorithms (code) developed in the paper tested on a small scale vehicle (1:43, F1TENTH, DonkeyCar, Deepracer, Formula Student) - yes/no
* Small car tested: Was the algorithms (code) developed in the paper evaluated in a simulation Environment
* Vehicle Type: Which type was the vehicle were the code was tested on
* Racing Series: To which autonomous racing series belongs the paper
* Paper Title
* Link to Paper


# LaTeX bibtex file
This repository includes a bibtex file called "AutonomousRacing_Literature.bib". This file contains all the papers from the excel file with their corresponding bibtex information (journal type, proceedings, year etc.).
The bibtex entry is named after the "Last Name Author" + "Year".
