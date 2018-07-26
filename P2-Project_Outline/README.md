# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview What will your app do? What might users find useful about it? Where did the idea come from?
	I am creating a webpage to maintain a meta analysis study. Meta-analysis synthesizes a body of research investigating a common research question. 	
The analysis will consist of a number (greater than two) of studies found in scientific journals. 
In order for a study to be included, it must meet predetermined criteria for the dependent and independent variables, 
null and alternative hypotheses, p-values etc. My starting dataset will be from author Daniel S. Quintana, 
who created simulated datasets. The simulated datasets are adapted from Molloy et al., (2014)**. 
	The webpage is useful because one can easily add, subtract and manipulate the data in an easy to use application. 
The user can also continue to add studies to the analysis as time goes on and new data emerges. 
The idea came from wanting ease of access of a webpage as well as the semi-Graphical User Interface benefits of R for diagnostics. 

**Molloy, G. J., O’Carroll, R. E., and Ferguson, E. (2014). Conscientiousness and Medication Adherence: A Meta-analysis. 
Ann Behav Med 47, 92–101. doi:10.1007/s12160-013-9524-4.		
	
### Features
1. User login: Users will be able to create accounts and log in to the application. Each user will have a profile page.
2. Search: Users will be able to search for different studies via keyword, title or ID
3. (MAYBE) Add Study with unique ID: Users will be able to add new study when logged in. 
	The study will have to meet the predetermined criteria of the meta analysis. 
	Each study will have a numeric ID.  
4. Delete Study: Users will be able to delete any number of studies to manipulate diagnostic tests
5. Run Graphs, Forest Plots, Funnel Plots, 
   Users will be able to run different diagnostic tests to identify outliers and influential cases
6. Check for Publication Bias: 
	Users will be able to run Regression Test for Funnel Plot asymmetry and Rank Correlation test for Funnel Plot asymmetry.  

### Technologies
C#
ASP.Net
R
SQLAlchemy

### What I'll Have to Learn
I will have to learn R with C#. My current problem is creating a database that can be added to. 
I would like users to add different values that must be verified before the database can accept them. 


### Project Tracker
https://github.com/m124248/liftoff-assignments/projects/1