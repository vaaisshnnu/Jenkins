# ![image](https://github.com/user-attachments/assets/796aaf3d-69ac-4f65-9d72-93f15dc43878) Personalized Jenkins Project Documentations - Created, Tested & Deployed ✅

Jenkins Freestyle Projects - Here you will have the Step by Step Documentation of the Jenkins Freestyle Projects done by me till now!

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)]()
[![Connect on LinkedIn](https://img.shields.io/badge/LinkedIn-GangaVaishnuReddy-blue?logo=linkedin)](https://www.linkedin.com/in/vaaisshnnu-reddy/)


This repository contains a collection of Jenkins Freestyle Projects with detailed steps and configurations. Each project demonstrates different Jenkins capabilities and integrations.

---

## Project Details ##

**** 1. Create a Shell Script and Execute It ****
Purpose:  
I want to create a Jenkins Freestyle Project to create a shell file from Jenkins dashboard in my EC2 and to create a file with the output followed.

Key Steps:
- Create a new Freestyle project.
- Add a build step to create and execute the shell script.
- Save the output to a text file.

Optional Enhancements:
- Archive the output file as a build artifact.
- Add email notifications for build success/failure.

---

**** 2. Jenkins build run an existing file which is present in my EC2 instance from GUI Dashboard ****
Purpose: 
Let's say you've an shell script which you've created in you ec2 instaance and You want Jenkis to run that file when you build a job in Jenkins GUI Dashborad

Key Steps:
- Create a new Freestyle project.
- Add a build step to Configure the Project
- Make sure the Jenkins user has execute permissions on the file.
- Save & Perform Build 

---

**** 3. Create and Run a Shell Script to install Apache server on my EC2 and Access web Page
Purpose: 
Create a shell script to install Apache, execute it, and save the output to a text file.

Key Steps:
- Create a new Freestyle project.
- Add a build step to create, execute the script, and log the output.
- Save and run the job.
- Verify Apache installation by accessing the default web page.

---

**** 4. Parameterized Build with Welcome Message ****
Purpose:  
Create a parameterized build that displays a custom welcome message.

Key Steps:
- Create a new Freestyle project.
- Enable parameterized build with a string parameter.
- Add a build step to display the welcome message.
---

**** 5. Throttle Build ****
Purpose:  
Restrict the number of concurrent builds to prevent resource exhaustion and conflicts.
Key Steps:
- Install the Throttle Concurrent Builds Plugin.
- Create a new Freestyle project.
- Configure throttle settings to limit concurrent builds.

---

**** 6. Integrate Public GitHub Repo ****

Purpose:  
Clone code from a public GitHub repository and list the contents.
Key Steps:
- Install the Git plugin.
- Create a new Freestyle project.
- Configure the GitHub repository URL.
- Add a build step to list the contents of the cloned repo.

---

**** 7. Build Code from GitHub Repo with Maven ****
Purpose:  
Clone code from a GitHub repository and build it using Maven- I want Jenkins to Integrate Public GitHub Repo to the EC2 instance (In Manual case, We manually type "git clone <git_hub_repo>" , Here we're automating this )
Key Steps:
- Install the Git and Maven Integration plugins.
- Create a new Freestyle project.
- Configure the GitHub repository URL.
- Add a build step to invoke top-level Maven targets.

---

## How to Use

1. Clone this repository to your local machine.
2. Follow the detailed steps for each project to configure and run the Jenkins jobs.
3. Customize the projects as needed for your specific use case.

## Connect

[![Connect on LinkedIn](https://img.shields.io/badge/LinkedIn-GangaVaishnuReddy-blue?logo=linkedin)](https://www.linkedin.com/in/vaaisshnnu-reddy/)

---

