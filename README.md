[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15289403&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

Step 1- Downloading the media criterion
(i) Make installation media for Windows 11.
Visit https://www.microsoft.com/software-download/windows11 to see the Windows 11 download page.
Click "Download now" in the "Create Windows 11 Installation Media" section.
(ii) Launch the Media Creation Tool.Launch the executable file of the downloaded Media Creation Tool. Accept the terms of the license.
(iii) Configure the Tool for Media Creation: Select the 64-bit architecture, edition, and language, then click the next button. To utilize "USB flash drive" as the media, select it. An alternative is to select "ISO file" in case you wish to make a bootable DVD.
(iv) Make the media for the installation: Put in a USB flash drive with a minimum capacity of 8 GB. Click "Next" after picking the USB disk from the list. The utility will produce a bootable USB stick and download Windows 11. Next, select "Finish."

Step 2- Installing Windows 11 using the installation media
(i) Get your computer ready: Make a backup of all crucial information. Make sure the specifications for Windows 11 are met by your computer.
(ii) Utilizing the USB drive to boot up: Put the USB bootable into your computer. Enter the BIOS/UEFI settings after restarting your computer (usually accomplished by using a key during startup, such as F2, F12, Delete, or Esc). Modify the boot sequence such that the USB drive boots first. 
(iii) Initiate the Installation Procedure: Exit the BIOS/UEFI settings after saving the modifications. This should boot your computer from the USB drive. It will display the Windows Setup screen. Click "Next" after making your keyboard preference, language, and time selections. Select "Install now."
(iv) Put in the product key here: Enter your Windows 11 product key if requested. You can skip this step if you're upgrading from Windows 10 because the activation should happen automatically. Choose the Installation Type. To ensure a clean installation, select "Custom: Install Windows only (advanced)". Select Windows type, then select Next.
(v) Divide the Drive: Choose the partition on which Windows 11 should be installed. To make a new partition, you can delete an existing one, but doing so will remove all of the data on the chosen disk. Click "Next" to launch the installation.

Step 3- Finish the Installation
(i) Observe the on-screen directions: Your computer will now be installed with Windows 11. Your computer may restart multiple times during the procedure, which could take some time.
(ii) Install Windows 11: You will be walked through the initial setup procedure after installation. Set up any extra options, sign in with your Microsoft account, and configure your preferences.


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

Downloading and Installing VS Code on Windows
(i) Visit https://code.visualstudio.com/Download to get the Visual Studio Code download.
(ii) Select "Download for Windows" from the "Download Visual Studio Code" section.

(iii) The VS Code installation (VSCodeUserSetup-x64-1.X64-1.XX.X.exe) will begin to download.
(iv) Open the VS Code installation that you downloaded.
(v) Launch VSCodeUserSetup-x64-1.X64-1.XX.X.exe to launch the VS Code installer. There will be an appearance of the installer wizard.
(vi) Click "Next" after accepting the license agreement.
(vii) Select the location where you wish to store the installation of VS Code. Click "Next" after accepting the default location.
(viii) Click Next after accepting the default Start Menu Folder.
(ix) Choose extra assignments (optional but advised):
-To create a desktop icon, click on it.
-Click "Add to path" (using the command line is crucial).
-For files that are supported, click Register Code as an Editor.
-Including the "Open with Code" option in the context menu of Windows Explorer.
-Including "Open with Code" in the context menu for the directory.
Then click Next.
(x) To start the installation, press the install button. The installion should take approximately a minute after you click the install button.
(xi) To complete the installation click "Finish." A setup window will show up upon installation. Then, you can click "Launch VS Code." 


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

Step 1- Downloading Git
(i) Visit https://git-scm.com/downloads to get the most recent Git version compatible with your system.
(ii) Launch the Git installation that you downloaded. Launch the "Git-2.38.0-64-bit.exe" installer for Git. There will be an appearance of the installer wizard. Click "Next" after accepting the license agreement. Select the directory where you wish to store the Git installation. Click "Next" after accepting the default location.
(iii) Observe the Installation Wizard's instructions: Select the default settings or alter the installation to suit your tastes. The important settings are:
-modifying the environment of your PATH.
-Selecting the transport backend over HTTPS.
-Setting up the conversions for line ends.
-Selecting the Git editor by default.
(iv) Launch the folder: A prompt to establish a start folder will appear. Click Next after leaving it as is.
(v) Text editors: Select your preferred text editor from the drop-down option (Notepad++, Vim, etc.)that works well with Git (we selected Vim) and click Next.
(vi) Select every default setting in the next steps, then click "Finish."
(vii) Verifying the Installation: Open Command Prompt or Git Bash and run git –version

Step 2- Setting Up Git
(i) Launch the command prompt (Git Bash) or terminal.
(ii) Configure your email address and username: [git config -wide user, name "Your Name"] [git config --global "your.email@example.com" user.email]

Step 3- Make an account on GitHub
(i) Visit https://github.com to create an account.
(ii) Enter the following details:
-username
-E-mail address
-Password
-Verify the password
-Make a GitHub account.
(iii) In order to confirm your email address, click the link.

Step 4- Initialize a Git repository
(i) Go to your profile on GitHub and click on your repositories. Click on “Create new repository”. Fill in the details:
-Repository name
-repository description
-select “Public”
-Select “Initialize this repository with a README” (optional)
-Add.gitignore (optional)
-Click on “Create repository”
-Choose a license (optional)
(ii) Click "Create repository".

Step 5- Cloning Git Repository
(i) From the GitHub website, copy the repository URL.
(ii) Launch the Command Prompt or Git Bash.
(iii) Execute the git clone repository URL.
(iv) To verify whether the repository has been successfully cloned, navigate to the cloned repository and run git status.
Using the ls command, confirm the cloning

Step 6- Adhere to and Promote Changes
(i) Create a new file
(ii) Fill the file with content
(iii) Save and close the editor. If you are working with VS Code, ensure it is on AutoSave alwats to ensure it automatically saves any changes you perform on the files you are working on.
(iv) Verify the repository's current state using [git status]
(v) To add the new file or changes you made, use [git add .]
(vi) Press the "git commit -m "Changes/Added a file" to commit the changes you made.
(vii) Use [git push -u origin master] to push the modifications to the remote repository.

-git ignore and .gitignore files are used to indicate the files that should not be pushed to the repository together with the code. They also avoid pushing the virtual environment you activate when creating a Djang project to the repository together with the project.

A Github repository with a sample project initialized with Git"https://github.com/MiriamWaithira/E-commerce_with_Django".


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.


Step 1- Downloading the Python installer
(i) Visit this link: https://www.python.org/downloads/ Get the most recent Python version for Windows.
(ii) Choose the installer that is compatible with the Python version you wish to set up.

Step 2- Launch the installer
(i) Launch the installer file that you downloaded.
(ii) Launch the installation.
(iii) Select the "Add Python to PATH" check box.
(iv) Select "Install Now."

Step 3- Check Installation
(i) Open Git Bash or Command Prompt.
(ii) Type python --version
(iii) Check the version number to make sure the installation is correct.


5. Install Package Managers:
   If applicable, install package managers like pip (Python).

The pip package manager is usually included in the installation package of Python 3.4 and later. This implies that pip is automatically included as part of the installation process when you install Python from the official Python website (https://www.python.org/).
(i) To make sure the pip is installed and current: [python -m install pip --upgrade pip]
(ii) Utilize pip to install the necessary packages: [python -m requirements.txt]
(iii) To utilize pip to install a package, type [pip install package-name] eg. [python -m pip install pillow]


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html


(i) Visit the Community Downloads page for MySQL.Installer: https://dev.mysql.com/downloads/ Get the most recent MySQL version for Windows.
(ii) Choose the installer that is compatible with the MySQL version you wish to set up.
(iii) Launch the Installer: After downloading, open the.msi file.
(iv) Select the Type of Setup: Click Next after selecting a configuration type (Developer Default, Server only, etc.).
(v) Verify the Requirements: The required dependencies will be installed and verified by the installer.
(vi) Setting up: To install the chosen MySQL products, click Execute.
(vii) Setup: Click "Next" to proceed to the MySQL server configuration. Select Independent MySQL Server
(viii) Click "Next" after selecting "Standalone MySQL Server / Classic MySQL Replication"
(ix) Networking and Type. Next, choose "Server Computer" under the "Config Type" field and press "Next"
(x) Authentication and passwords: Click "Next" after selecting "Use Strong Password Encryption for Authentication"
(xi) Accounts and Roles: You must enter the root user's (administrator's) password in the next box. Additionally, if needed, you can add more users here by clicking the "Add User" button. Do not click the "Add User" button for now. Click "Next" once the password has been entered.
(xii) We click "Next" and maintain all the default options for the following step
(xiii) Configuring the MySQL server: The MySQL server settings must then be applied by selecting "Execute".
(xiv) Finish. Ultimately, press "Finish" to finish the installation.


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.


Step 1- Using Docker is to install it.
(i) Docker Desktop can be downloaded and installed from the Docker website.
(ii) Once the installation is complete, launch Docker Desktop.

Step 2: Check the Installation of Docker
(i) Open Git Bash or Command Prompt.
(ii) Use the docker --version command.
(iii) Check the version number to make sure the installation is correct.


8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.


SQLTools: Interacts with databases directly from VS Code.
IntelliSense for CSS class names in HTML: Adds autocomplete for CSS class names.
Code Runner: Runs code snippets or entire files directly from VS Code.
Prettier: Formats code automatically based on defined rules.
Python: Provides IntelliSense, linting, and debugging for Python files.
Pylance: Enhances Python language support.
HTML Snippets: Provides quick access to common HTML code snippets.
CSS Peek: Navigate to CSS definitions from HTML files.
Docker: Manages Docker containers, images, and Dockerfiles within VS Code.
Got it! Here are the descriptions with the extension and its function on the same line:
Flutter: Provides support for Flutter development, including tools for creating, testing, and running Flutter applications.
Django Template: Adds syntax highlighting and snippets for Django template language, enhancing the development experience for Django projects.
Oracle Developer Tools for VSCode: Offers tools and features for developing and managing Oracle database applications, including SQL editing and PL/SQL support.
SQL Bindings: Helps bind SQL queries to data sources within your code, providing better integration and management of SQL code.
Data Workspace: Allows managing and interacting with multiple data sources within a single workspace, improving data project organization.
Dart: Provides comprehensive support for Dart programming, including code analysis, debugging, and code completion.


9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 


Customizations for flutter and MySQL installation
(i) After extracting the Flutter SDK, find the flutter directory. For example, C:\src\flutter.
(ii) Update System Environment Variables:
-Click on the windows button on the keyboard and type 'Environment Variables'
-Select 'Edit the system Environment Variables'
-Click 'Environment Variables'
-In the System variables section, find and select the 'Path' variable, then click 'Edit'.
-Click 'New' and add the path to the flutter/bin directory. For example, 'C:\src\flutter\bin'. For MySQL use 'C:\Program Files\MySQL\MySQL Server 8.0\bin.'
-Click 'OK' to save and close all dialogs.
(iii) Verify:
Open a new Git Bash or PowerShell window and run 'flutter doctor' to verify that Flutter is correctly added to the PATH
or 'mysql --version' for MySQL.

Challenges encountered during the setup of the E_commerce project
**** The terminal opening in the wrong current working directory (cwd) of VSCode ****
After working on the codes for the project, making changes and building up on it, I wanted to make migrations through the VSCode terminal. So by opening a new terminal (with Git Bash as Default), the VSCode terminal opened here:
"(2mayproject)
Kamiri@DESKTOP-TRO6B58 MINGW64 C:/Users/Kamiri/AppData/Local/Programs/Microsoft VS Code"
Instead of here:
"(2mayproject)
Kamiri@DESKTOP-TRO6B58 MINGW64 /d/2ndDjangoMayProject/Theproject"

**** The solution for the challenge ****
-Typing cd ../../.. on the Git Bash terminal to go out of that directory
-Using cd d:/2ndDjangoMayProject/Theproject to navigate into the right directory and work from there.


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
