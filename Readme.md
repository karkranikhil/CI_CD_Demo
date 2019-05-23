## What is Build - 
1) Compilation
2) Test execution
3) Database Integration
4) Code Inspection  - Dead code, Eslint
5) Automated Deployment - It is a good enhancement 
6) Document Generation 

## Continous Integration flow
1) Developer Commit change to VCS(git)
2) Then code will pulled by Dedicated build server that run the build processes
3) If all go well it deploy but if fail go back to developer

Generally We distribute all build task to different severs(VMs integration, test, UAT, production)

## CI stater kit need
1) Automated Build process
2) Automated Test Suit
3) Source code Repository   
4) Continous Build Server

## Famous CI tools
1) Jenkins
2) Bamboo
3) Hudson
4) TeamCIty
5) Visual Studio

##Why Jenkins
1) Easy install, easy upgrade, easy configuration
2) Distributed Builds
3)Monitoring external jobs
4)No limits to the number of jobs
5)Plugin architecture
6)Jenkins provides API to its functionalities
7)Can be scripted itself

## DOwnload 
https://jenkins.io/


## Build Tool
Maven - Maven is a build automation tool used primarily for Java projects. Maven addresses two aspects of building software:
brew install maven
ANT - Apache Ant is a software tool for automating software build processes, which originated from the Apache Tomcat project in early 2000.
brew install maven

##Creating First Jenkin job
1) New Item ->enter item name -> Freestyle project -> ok
2) Configuration save
3) click Build Now
3) Build history show's build running->click build
4) see console output for the build

## How to pass Build
write exit 0

##Where plugins helps you.
1) It helps in sending different types of reports
2) Send notifications
3) helps in deployment
4) Build Triggers
5) Code quality Analyzer

** plugin file format is .hpi - hudson plugin interface

Ypou can pinned a plugin by saving it as git.hpi.pinned. SO when ever jenkins upgrate version of git will remain same

## Configuration
manage jenkins -->configure
1) Executors - No of concurrent bill's you want to run.
2) You can Env variable 
3) maven configuration - 