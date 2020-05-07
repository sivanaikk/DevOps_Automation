# DevOps_Automation
Home work for the DevOps 

### Automation of the Deployment of Website 


## Tools Used 
# Git and GitHub
# Jenkins
# Docker 



 
** Git and GitHub **

Used git and GitHub as SCM 
Used the Poll SCM for post-commit to automated the push to GitHub


Created branches 

Master 
Dev


Created two jobs with Jenkins to 

# job 1

To copy the files from the workspace of Jenkins to local folder and deploy the webserver by using the docker image of the httpd 

This job run if  any containers are not running 

# job 2 

To copy files from workspace of Jenkins to the folder and deploy the code  for Quality Assurance for Testing 
If this builts good 
Post built triggers and merge the code of Dev to the master 
