# University Enrollment Estimator
Supervised learning model to estimate university enrollments based on 
institutional attributes.  Developed as a capstone project for Udacity's
Machine Learning Engineer Nanodegree Program in October 2016.

## Libraries
This project requires *Python 2.7* and the following Python libraries installed:

* NumPy

* Pandas

* scikit-learn


## Quick Start
For most users, there are two primary files of interest.

* 'report.pdf' -- Contains the analysis of the various models developed, along
with comparisons of their various performances.  Also explains much of the
decision making process while developing this model.

* 'enrollment_estimator.ipynb' -- A Jupyter Notebook, containing all of the
Python code to produce the various Regression models and relevant analytics.

In addition, users will need to acquire the Integrated Postsecondary Education 
Data System (IPEDS) Delta Cost Project Database from 2000-2012.  It can be
downloaded from here: http://nces.ed.gov/ipeds/deltacostproject/download/IPEDS_Analytics_DCP_87_12_CSV.zip

After downloading, unzip the archive, and place the files
'delta_public_87_99.csv' and 'delta_public_00_12.csv' in the same folder as 
'enrollment_estimator.ipynb'.

## More Information

For additional information about the IPEDS Delta Cost Project, see:
http://nces.ed.gov/ipeds/deltacostproject/