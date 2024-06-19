[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15288368&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
1.	How to download Windows 11
a)	Download and run the PC Health Check here (aka.ms/GetPCHealthCheckApp). This is the official, Microsoft-developed application to check if your PC meets all the hardware requirements to update.
 
b)	Run the app after it has completed installation, and click Check now.
If your PC meets the requirements, it should display a green checkmark stating that your PC is compatible.
 
c)	Back up your PC just in case. Your upgrade to Windows 11 should be smooth and seamless, but just if something goes wrong, backing up will ensure you don't lose any of your files.

 
d)	Head to the official download website (www.microsoft.com/en-us/software-download/windows11).
 
e)	Select your download option. The recommended one is the Installation Assistant—this is the same as what you would use if you upgraded via Settings.
•	The Installation Media is used if you want to clean install your PC, and the ISO is used as a virtual machine. The recommended and easiest option is the Installation Assistant.
 


f)	Follow through with the process. You'll be prompted with a license agreement, which you need to accept. Then, a window will pop up, in which the download will take place.
•	The three steps that will take place in the download window will be "Downloading," "Verifying Download," and lastly "Installing." This process can take up to a few hours depending on your PC.

 
g)	Restart your PC. After it is done installing, the window will prompt you to restart your PC and start a countdown of 30 minutes. Simply hit "Restart now."
 
h)	Let your PC install Windows 11. Your computer will automatically run the installation process.
•	Do not shut down your computer, and be sure to keep it plugged in throughout the process.
 
i)	Complete! After installation, the Windows 11 start-up screen will appear. Log in as you normally would and start exploring the new features of Windows 11.


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
Step 1: Visit the Official Website of the Visual Studio Code using any web browser like Google Chrome, Microsoft Edge, etc.

 
Step 2: Press the “Download for Windows” button on the website to start the download of the Visual Studio Code Application.

Step 3: When the download finishes, then the Visual Studio Code Icon appears in the downloads folder.
 
Step 4: Click on the Installer icon to start the installation process of the Visual Studio Code.
Step 5: After the Installer opens, it will ask you to accept the terms and conditions of the Visual Studio Code. Click on I accept the agreement and then click the Next button.
 
Step 6: Choose the location data for running the Visual Studio Code. It will then ask you to browse the location. Then click on the Next button.
 
Step 7: Then it will ask to begin the installation setup. Click on the Install button.
 
Step 8: After clicking on Install, it will take about 1 minute to install the Visual Studio Code on your device.
 
Step 9: After the Installation setup for Visual Studio Code is finished, it will show a window like this below. Tick the “Launch Visual Studio Code” checkbox and then click Next.
 
Step 10: After the previous step, the Visual Studio Code window opens successfully. Now you can create a new file in the Visual Studio Code window and choose a language of yours to begin your programming journey!

 
So this is how we successfully installed Visual Studio Code on our Windows system.


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   Step 1:Download the latest version of Git and choose the 64/32 bit version. After the file is downloaded, install it in the system. Once installed, select Launch the Git Bash, then click on finish. The Git Bash is now launched.
 
Step 2:
Check the Git version:
$ git --version
Step 3:
For any help, use the following command:
$ git help config
This command will lead you to a browser of config commands. Basically, the help the command provides a manual from the help page for the command just following it (here, it's config).
Another way to use the same command is as follows:
$ git config --help
Step 4:
Create a local directory using the following command:
$ mkdir test
$ cd test
Step 5:
The next step is to initialize the directory:
$ git init
Step 6:
Go to the folder where "test" is created and create a text document named "demo." Open "demo" and put any content, like "Hello Simplilearn." Save and close the file.
Step 7:
Enter the Git bash interface and type in the following command to check the status:
$ git status
Step 8:
Add the "demo" to the current directory using the following command:
$ git add demo.txt
Step 9:
Next, make a commit using the following command:
$ git commit -m "committing a text file"
Step 10:
Link the Git to a Github Account:
$ git config --global user.username
Note: simplilearn-github is the username on the Github account.
Step 11:
Open your Github account and create a new repository with the name "test_demo" and click on "Create repository." This is the remote repository. Next, copy the link of "test_demo."
Step 12:
Go back to Git bash and link the remote and local repository using the following command:
$ git remote add origin <link>
Here, <link> is the link copied in the previous step.
Step 13:
Push the local file onto the remote repository using the following command:
$ git push origin master
Step 14:
Move back to Github and click on "test_demo" and check if the local file "demo.txt" is pushed to this repository.
Additional Customization Options
This option enables users to add extra elements such as symbolic links for command lines. Nevertheless, one should always prefer default options for shortcuts or more. 
There are some experimental options available such as pseudo control Support or Built in file system monitor concerning your installed Git version.  
How to Launch Git in Windows?
There are two methods to launch git in windows. One is launching git using a bash scripting shell with the help of the command line and another is launching git using a graphical user interface. 
To launch git via bash scripting shell,
First, open the window and search for git bash and open it.
To launch git via graphical user interface(GUI), similarly, first open the window and search for git GUI and click on the application icon and open it. 
Configure GitHub Credentials
You can configure your local GitHub installation with credentials by using the following commands. Also, don't forget to add your own GitHub credentials for username and email address. 
git config –global user.n
ame "github_username" 
git config –global user.e
mail "email_address"
Clone a GitHub Repository
Initially you need to click the options repository on GitHub. 
Then in the top right corner, click the option clone or download where a small drop-down box will appear having a URL for cloning over HTTPS. 
Then enter into your Powershell windows and write clone URL as:
git clone repository_url 
On the other hand, you can clone a github repository with SSH URLs where first you need to generate an SSH key pair on your windows workstation as well as need to assign a public key to your GitHub account. 
List Remote Repositories
Make a copy of the repository from GitHub for your working directory. 
Ensure that the working directory should have the project name as
"cd git_project" and replace the project name from the downloaded repository. 
If the above option doesn't work, you can list the content using "ls command" for the current directory, especially to check your exact number of spellings. 
Besides, you can list the remote repository in the sub-directory as "git remote -v". 
Summary: Steps For Git Installation on Windows 10
Download and install Git
Git bash interface
Basic Git commands
Create a local repository
Connect to the remote repository
Push the file to GitHub


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
How to Install Python on Windows With Python Installer
1.First, go to the Python website and click on the “Download Python” button. Select the latest version. As of this writing, that would be Python 3.11.4. 
 
2.Select the “Windows installer” option and click on the “Download” button. Once the download is complete, run the installer.
 
3.During the process, it’s advisable to check the boxes “Use admin privileges when installing py.exe” and “Add python.exe to PATH” to save the trouble of manual adjustments in the environment variable later.
4.Then, follow the on-screen instructions to install Python. Once the installation is complete, you should see a success message like this:
 
5.You can verify that Python has been installed by opening a command prompt and typing the following command: python -V.
 
6.This will display the Python version currently installed.


5. Install Package Managers:
   If applicable, install package managers like pip (Python).
. How to install pip
Ensure you can run pip from the command line
Additionally, you’ll need to make sure you have pip available. You can check this by running:
   Windows
py -m pip --version
If you installed Python from source, with an installer from python.org, or via Homebrew you should already have pip. If you’re on Linux and installed using your OS package manager, you may have to install pip separately, see Installing pip/setuptools/wheel with Linux Package Managers.
If pip isn’t already installed, then first try to bootstrap it from the standard library:
   Windows
py -m ensurepip --default-pip
If that still doesn’t allow you to run python -m pip:
•	Securely Download get-pip.py [1]
•	Run python get-pip.py. [2] This will install or upgrade pip. Additionally, it will install Setuptools and wheel if they’re not installed already.


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
Download and Install MySQL for Windows Steps
Step 1: Visit the Official MySQL Website
Open your preferred web browser and navigate to the official MySQL website. Now, Simple click on first download button.

 
Step 2: Go to the Downloads Section
On the MySQL homepage, Click on the ” No thanks, just start my download” link to proceed MySql downloading.

 
Step 3: Run the Installer
After MySQL downloading MySQL.exe file , go to your Downloads folder, find the file, and double-click to run the installer.
 
Step 4: Choose Setup Type
The installer will instruct you to choose the setup type. For most users, the “Developer Default” is suitable. Click “Next” to proceed.

 
Step 5: Check Requirements
You might be prompted to install necessary MySQL software, typically Visual Code. The installer can auto-resolve some issues, but not in this case.

 
Step 6: MySQL Downloading
Now that you’re in the download section, click “Execute” to start downloading the components you selected. Wait a few minutes until all items show tick marks, indicating completion, before moving forward.

 
Step 7: MySqL Installation
Now the downloaded components will be installed. Click “Execute” to start the installation process. MySQL will be installed on your Windows system. Then click Next to proceed

 
Step 8: Navigate to Few Configuration Pages
Proceed to “Product Configuration” > “Type and Networking” > “Authentication Method” Pages by clicking the “Next” button.
Step 9: Create MySQL Accounts
Create a password for the MySQL root user. Ensure it’s strong and memorable. Click “Next” to proceed.

 
Step 10: Connect To Server
Enter the root password, click Check. If it says “Connection succeed,” you’ve successfully connected to the server.

 
Step 11: Complete Installation
Once the installation is complete, click “Finish.” Congratulations! MySQL is now installed on your Windows system.

 
Step 12: Verify Installation
To ensure a successful installation of MySQL, open the MySQL Command Line Client or MySQL Workbench, both available in your Start Menu. Log in using the root user credentials you set during installation.
MySQL Workbench Is Ready To Use
MySQL is an open-source relational database management system that is based on SQL queries. MySQL is used for data operations like querying, filtering, sorting, grouping, modifying, and joining the tables present in the database. 


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
Browse for extensions
You can browse and install extensions from within VS Code. Bring up the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of VS Code or the View: Extensions command (Ctrl+Shift+X).
 
This will show you a list of the most popular VS Code extensions on the VS Code Marketplace.

 
Each extension in the list includes a brief description, the publisher, the download count, and a five star rating. You can select the extension item to display the extension's details page where you can learn more.
Note: If your computer's Internet access goes through a proxy server, you will need to configure the proxy server. See Proxy server support for details.
Install an extension
To install an extension, select the Install button. Once the installation is complete, the Install button will change to the Manage gear button.


9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
. GITHUB REPOSITORY SAMPLE PROJECT
 

Steps to Initialize and Push to GitHub
1.	Navigate into the Git repository locally:
# cd c:/EGHL
Then add touch .gitignore

# Add the README.md and .gitignore files
git add README.md
git add .gitignore

# Commit the files
git commit -m "Initial commit"

# Add a remote repository (replace <username> and <repo> with your GitHub username and repository name)
git remote add origin https://github.com/<username>/<repo>.git

# Push the committed files to the remote repository
git push -u origin main
2.	Verify on GitHub:
o	After pushing, visit your repository on GitHub (https://github.com/GeorgeWaweruKiarie/EHGL.git) to see the README.md and .gitignore files listed.
My repository link is https://github.com/GeorgeWaweruKiarie/EHGL.git


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
