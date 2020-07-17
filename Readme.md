# Domino curriculum

This repository contains a course for learning [Domino Data Lab](https://docs.dominodatalab.com/en/4.2/).

Recorded Demo of Domino:
 - [link](https://dominodatalab.zoom.us/rec/play/uMF_deCo_D03SIGd5gSDU6QtW460famsgHcdqPYPykfgUSUCZwHwZudDauYhg61yjIp9o4p0JQcOKrWc?continueMode=true)
 - password: 4R*8MJ*T

The features highlighted in this course include:

 1.	Python/R work environments (combining Python and R, Python Dash and R Shiny dashboards)
 2.	Elastic compute to launch light and heavy calculations side by side and scale up and down as needed
 3.	Developing and deploying model endpoints
 4.	Scheduling and running repeatable reports, tweaked by use of parameters. E.g., multiple versions of a "performance tracker" deck
 5.	Easy interfaces for business users - to give business analysts and product managers the ability to monitor and update processes directly
 6.	Using Spark with Jupyter and Zeppelin
 7.	Building a deep learning application and training the NNs on GPUs.
 8.	Auto ML - using automation to train and deploy multiple models, tune hyper-parameters, and pick the best predictor using cross validation
 9.	Reproducing experiments by retrieving the data, code and other artifacts that were part of the original project. Also, employ this to demonstrate knowledge sharing by having one set of users deploy and update models built by others.
 10.	Model lifecycle - using the platform to practice implementing all phases of a model lifecycle – data prep, feature extraction, model selection, training, validation, deployment and governance.

## This course will be developed in phases:

### Phase 0:
One or more members of EIDS gains preliminary familiarity with the most aspects of Domino. Tutorials and documentation will be generated as appropriate.

### Phase 1:
Building on the lessons learned in Phase 0, a core group drawn from the union of EIDS and other teams will work collaboratively on 3-4 carefully selected projects.   The scope of the projects will be molded to cover the most important features of Domino (e.g., dashboards, model lifecycle, distributed computing) we want to master during the trial.

Projects will be executed within a team consisting of multiple archetypical roles **(team structure is up for debate)**:
  - Stake holder - A non-technical person respresenting the line of business
  - End user - A minimally technical business analyst or product manager who consumes the dashboard and end points
  - Data scientist - Person responsible for the modelling
  - Engineer - Responsible for standing up and testing the final dashboards and end points

Running multiple (3-4) projects simultaneously will allow each member of the core group to play technical and non-technical roles in a project. Each participant will benefit from exposure to the technical and business aspects of a data science project.

Prospective projects and data sets include  **(fierce debate is required here to get the project scope and the data source right)**:


| Project               | Owner       | Description |  Dataset(s) |
| -----------           | ----------- | ---------   | ----------  |
| Transactions          |  Bob       | Detect fraud transactions and money laundering. | [kaggle](https://www.kaggle.com/apoorvwatsky/bank-transaction-data) |
| NPS                   |             |             |             |
| Network growth        |             |             |             |
| Recommendation engine |             |             |             |
| Name matching         |             |             |             |
|                       |             |             |             |
|                       |             |             |             |



Core group members will be expected to carefully document all the steps and progress made.  These materials will be used to derive data science lectures and demonstrations given to broader audiences.

### Phase 2 (Subject to approval):

In this phase, knowledge is transferred to broader audiences through multiple channels, including:
 - project demos
 - weekly data science lectures (ideally given by different members of the core group)
 - mentorship of other teams that want to practice building and deploying their own data science project
