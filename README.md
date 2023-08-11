# 3.12CDserverless_v2

in git hub action files

name: # is the name of the action
actor: is the person to .....

on: push: branch
#on main branch and other branch (because *, so any branch can)  it'll use this workflow

Job is a set of steps in workflow that'll be exercuted with the same workflow
runs on is the configuration 

predeploy is not a keyword, and can be anything - it'll appear on the pipeline. 


___________code----------

name: CICD for Serverless Application-title of action
run-name: ${{github.actor}} is doing CICD for serverless application

on: 
  push:
    branches: [ main, "*"]



  
