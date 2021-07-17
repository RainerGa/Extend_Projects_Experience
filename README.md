# Extend_Projects_Experience
Experience with the extension of available projects

# Who am I
I am a Java Developer. Not as my primary job :-) But in our Company I develop, in the past, Software Products for 500 concurrend endusers. 
Over the time my Job changes from development and systemadministration to a management position. Now it is more a hobby and I dont want lose my skill.

# Why
Over the last few months I have tried to expand, adapt or correct some open source projects. Here I would like to tell you about my experiences and give you a few tips on what would facilitate the entry for those outside the project.

# My Experiences

## A) Development Environment
### Actual status
Github supports the developer with the information which programming language is used in the respective project. But there is no information about the development environment.
### Problem
For the expansion of a project in a (for yourself) foreign programming language, this is extremely important information. Or in a different way overall: Adding a command line parameter to software is actually an easy exercise. Only not if the development environment is not right. It takes too much time to research!
### Solution Variant I
**Add a File to your Project:**                 *dev_env.txt*

Content:

            Operating System
            [Operating System] [Version]
            
            Install Software
            [Install Software] [Version] [Link]

Example:

            Operating System
            Ubuntu 16.04
            
            Install Software
            OpenJDK 16 https://adoptopenjdk.net
            Eclipse IDE 2021-06 https://www.eclipse.org/downloads/download.php?file=/oomph/epp/2021-06/R/eclipse-inst-jre-win64.exe
            
### Solution Varian II
**Develop a Software** :grinning:

This software should consist of two parts. 
#### Part One
Analyse automatically the development environment for an Project.

**Idea**
In Eclipse there is an `.project` File. Does this contain all the necessary Informations?! And does the Information about the IDE be sufficient?!
How does other IDEs work?! 

#### Part Zwo
Create the development environment automatically (install the correct software).

**Idea** 
It is easier to create/download a virtual development appliance? 

