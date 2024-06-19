[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15283481&assignment_repo_type=AssignmentRepo)
# Developer Environmental Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download.
* Open web browser and navigate to https://code.visualstudio.com/.
* On the homepage, click the download option on the right corner.
* Chose option for Windows 10, 11 on the pag.e
* Once the download is done, run the installer and follow the on-screen instruction to complete the installation.
* Launch Visual code.

3. Set Up Version Control System:
Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

* Download latest Git version for windows on https://www.git-scm.com/downloads.
* Once its done downloading, run the the installer (.exe file).
* Follow the prompts to complete the installation.
* To confirm installation, open command prompt (Run as administrator) and write “git --version” and press Enter to confirm installation and version of Git installed. 
 
To configure on local machine (add your name and email address):
* Open command prompt (press start button, search command prompt and run as administrator).
* Write the below commands to set your name and email address:
   * git config --global user.name "Name"  (Replace “Name” with you name).
   * git config --global user.email "Email address" (Replace “Email” with your email address)
* Once completed, check your configuration setting using the command
   * Git config --list

4.Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

* Go to webpage and search https://www.python.org/.
* Click on downloads and choose your operating system. 
* Select the latest python and download.
* Once download is done, double click on it and install.
* Customize the installation by checking the box on Add Python 3.8 to PATH. 
* Follow the prompts until installation is done.
* To confirm installation, Open command prompt and write the command below:
   * python --version

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
Install virtual environment:
* Open Git bash.
* Write the command to create virtual environment: python -m pip install virtualenv.
* To activate virtual environment, write command: source myenv/Scripts/activate.

6. Configure a Database (MySQL):
   * Download and install MySQL database on https://dev.mysql.com/downloads/windows/installer/5.7.html
   * I could not configure a database

7.Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
For DART installation:
* Open your web browser and search https://dart.dev/get-dart/archive.
* Under Stable channel click on the below version and download the file:
   * version 3.3.1, OS=Windows, Architecture=IA32.
* Once Zip file is downloaded (in download file), copy it and paste it in your local drive/Windows drive.
* Extract the compressed file to the drive.
* On the extracted file, open bin file and copy the directory path at the top of the folder (C:\dart-sdk\bin).

To set up the path in environment variables:
* Go to start and search Edit system Environment Variables and select it.
* Click on Environment variables.
* Under User variables, double click on Path to add new variable.
* Click on New.
* Paste the directory path copied for Dart, click OK

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

The following Extensions were added to VS code:
* Flutter-https://dartcode.org/
* mplsstyle(Matplotlin)-
* Prettier-https://prettier.io/ 

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
