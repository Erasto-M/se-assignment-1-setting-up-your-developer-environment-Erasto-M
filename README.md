[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15276278&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

## PLP SOFTWARE ENGINEERING 
## Setting Up Developer Environment
1. Select Your Operating System (OS): Choose an operating system that best suits your preferences and project requirements. 
### Steps for downloading and Installing Ubuntu
### a. Check your System Requirements
- Ensure your computer meets the system requirements for Ubuntu:
- 2 GHz dual-core processor
- 4 GB RAM
- 25 GB of free hard drive space
## Backup your Data
- Backup all important data from your computer to avoid any loss during the installation process.
## Download Ubuntu
- Go to the Ubuntu Download Page.
- Click on "Download" to get the latest version of Ubuntu.
![alt text](image.png)
## Create installation Media
## Using Rufus (for Windows users):
- Download and install Rufus.
- Insert a USB flash drive (minimum 4 GB).
- Open Rufus and select the downloaded Ubuntu ISO file.
- Choose the USB flash drive as the destination and click "Start" to create the bootable USB drive.
## Using Balena Etcher (for macOS and Linux users):
- Download and install Balena Etcher.
- Insert a USB flash drive (minimum 4 GB).
- Open Etcher, select the downloaded Ubuntu ISO file, choose the USB flash drive as the destination, and click "Flash!" to create the bootable USB drive.
![alt text](image-1.png)
## In the above, select the Etcher for  linux
![alt text](image-2.png)
## Prepare your Personal Computer for Installation
- Insert the USB flash drive containing the Ubuntu installation media into your PC.
- Restart your computer.
- Enter the BIOS/UEFI settings (commonly accessed by pressing keys like F2, F12, Delete, or Esc during startup).
- Change the boot order to boot from the USB drive first.
## Install Ubuntu
- Boot from the USB drive and follow the installation instructions as shown in the screenshots below.
![alt text](image-3.png)
![alt text](image-4.png)
![alt text](image-5.png)
### Use wired connection in the case where you have an ethernet cable with internet connected to your pc
![alt text](image-6.png)
![alt text](image-7.png)
![alt text](image-8.png)
![alt text](image-9.png)
![alt text](image-10.png)
![alt text](image-11.png)
![alt text](image-12.png)
![alt text](image-13.png)
![alt text](image-14.png)
2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio
   - In linux , you can download the vscode from the ubuntu software   or you can also use commands in the terminal

###  a. Open the ubuntu software
![alt text](image-15.png)
### b. Search for vscode in the ubuntu software 
![alt text](image-16.png)
### c. Click code then click install 
![alt text](image-17.png)
![alt text](image-18.png)
### d. It has successfully installed 
![alt text](image-19.png)
###  From the terminal it also shows that it is installed 
![alt text](image-20.png)
### Also from the desktop when I search 
![alt text](image-21.png)
### You can now open it to test . just use your terminal and open it
![alt text](image-22.png) 
![alt text](image-23.png)


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
  ### a.  Run this command in the terminal to install git . and enter your password 
![alt text](image-24.png)
### b.  Check git version to confirm installation
![alt text](image-25.png)
### c. Create github account and create a new repository , enter the repository name , set it as either public or private depending on your needs
![alt text](image-26.png)

### d. Create a folder and open it in vscode , add files to it and then push to Github
![alt text](image-27.png)
### Open it in visual studio code and create two files and then initialize the github repository
![alt text](image-28.png)
### Add the files to tracking , make commits and finally push to the repository  you had created in github
![alt text](image-29.png)
### I faced some challenges ,  had not set the branch main to my local repository , that's why I set it after the second error 
![alt text](image-30.png)
4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  ## a. Install python in ubuntu using the terminal  and its respecti![alt text](image-31.png)ve installer 
  ![alt text](image-33.png)
  ###  Validate their Installation
![alt text](image-34.png)
###  c. Install Virtual environment using this command
![alt text](image-35.png)
### d. Validate its installation
![alt text](image-36.png)

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   ##  Already installed using the procedure above for installing python 
   ![alt text](image-37.png)
   ![alt text](image-38.png)

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   ### a. Install by  running this command   the terminal
   ![alt text](image-39.png)
   ### b. Configure MySQL Server:
   
During the installation process, you will be prompted to set a root password for MySQL. Choose a strong password and remember it.



    c. Secure MySQL Installation (Optional but Recommended):
            MySQL comes with a script to secure the installation. Run the following command and      follow the prompts to secure your MySQL installation:

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
