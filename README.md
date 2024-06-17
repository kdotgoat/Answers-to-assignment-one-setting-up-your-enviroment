[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15279377&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

SOLUTIONS AND STEPS

   1. **Check System Requirements**: I made sure my computer meets the system requirements for Windows 10. I these requirements on the Microsoft website.
   2. **Download Windows 10**: I visited the Microsoft website or used the link provided to download the Windows 10 installation file since it was a more stable version.
   3. **Create a Bootable USB Drive**: Use a tool like Rufus or the Media Creation Tool to create a bootable USB drive with the Windows 10 installation files.

   4. **Set USB as Primary Boot Device**: Insert the bootable USB drive into your computer and restart it. Access the BIOS settings and set the USB drive as the primary boot device.
   5. **Start Installation**: Follow the on-screen instructions to begin the installation process. Choose your language, time format, and keyboard layout.
   6. **Enter Product Key**: If prompted, enter your Windows 10 product key.

   7. **Select Installation Drive**: Chose the drive where i wanted to install Windows 11 and create partitions if necessary.

   8. **Complete Installation**: Let the installation process run. My computer may restarted several times during this process.

   9. **Set Up Windows 10**: Follow the on-screen instructions to set up Windows 10, create user accounts, and customize settings.

   10. **Update Drivers and Software**: After installation, i made sure to update drivers and software for optimal performance.



2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

SOLUTIONS AND STEPS
   
   1. **Download Visual Studio Code**: I  visited the official Visual Studio Code website at https://code.visualstudio.com/Download.

   2. **Select Your Operating System**: Chose the version of Visual Studio Code that matched my operating system (Windows 10) and clicked on the download button.

   3. **Run the Installer**: Once the download was complete, i ran the installer for the file i downloaded.

   4. **Follow Installation Instructions**: Followed the on-screen instructions to install Visual Studio Code on my computer, and did the customization where needed.

   5. **Launch Visual Studio Code**: After the installation was complete, I launched the Visual Studio Code from my desktop or applications folder.

   6. **Set Up Preferences**: I customized my  preferences, themes, and extensions in Visual Studio Code to tailor it to my coding needs.

   7. **Start Coding**: Began coding in Visual Studio Code by creating a new file or opening an existing project.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

SOLUTIONS AND STEPS

   1. **Install Git**: Started by downloading and installing Git on my local machine. You can download Git from the official website: https://git-scm.com/downloads. Follow the installation instructions for your operating system.

   2. **Create a GitHub Account**: Headed  over to https://github.com and created a GitHub account. Filled in the required details to set up my account.

   3. **Configure Git**: Once Git is installed, configured it on my local machine by setting up my username and email address. You can do this also  by running the following commands in your terminal:
      ```
      git config --global user.name "Your Name"
      git config --global user.email "youremail@example.com"
      ```

   4. **Initialize a Git Repository**: Navigated to the directory of my project in the terminal and initialized a Git repository by running:
      ```
      git init
      ```

   5. **Make Your First Commit**: Added my files to the staging area with `git add .` and commited them with a meaningful message using:
      ```
      git commit -m "Initial commit"
      ```

   6. **Connected to GitHub**: I Linked my local repository to a remote repository on GitHub. I did this by creating a new repository on GitHub and following the instructions to add a remote repository.

   7. **Push Your Code to GitHub**: Pushed my code to GitHub by running:
      ```
      git remote add origin <repository_URL>
      git push -u origin master

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

SOLUTIONS AND STEPS
      1. **Download Python**: I visited http://www.python.org on my web browser.
      2. **Choose Your Version**: Selected the version of Python i wanted to download. Typically, it was recommendeded to download the latest stable version.
      3. **Download Python**: Looked for the download link for my operating system (Windows, macOS, or Linux) and clicked on it to start the download.
      4. **Run the Installer**: Once the download was complete, I ran the installer by double-clicking the downloaded file.
      5. **Install Python**:I  Followed the installation wizard instructions. Made sure to check the box that says "Add Python to PATH" during installation.
      6. **Verify Installation**: After installation,i  opened a terminal git bash and typed `python --version` to verify that Python was installed correctly.
      7. **Install Additional Tools**: Depending on my project requirements, it was needed to install additional packages or tools using Python's package manager, pip.


5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   SOLUTIONS AND STEPS

      1. **Check Python Installation**: I first, ensured that Python was installed correctly by typing `python --version` in the Command Prompt or Terminal.
      2. **Download get-pip.py**: I used the following command to download the `get-pip.py` script:
         
      3. **Install pip**: Run the `get-pip.py` script using the following command:
         ```
         python get-pip.py
         ```
      4. **Verify Installation**: After the installation was complete, I c verified that pip is installed by typing `pip --version`.


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   SOLUTIONS AND STEPS

   1. **Download MySQL Installer**: I visited the MySQL download page at https://dev.mysql.com/downloads/windows/installer/5.7.html
2. **Select Installer**: Chose the MySQL Installer for Windows from the download options.
3. **Download and Run Installer**: Once the download was complete,i ran the installer by double-clicking the downloaded file.
4. **Choose Setup Type**: During installation,i  selected the setup type. You can choose either the Full, Custom, or other setup types based on your requirements.
5. **Select Products**: In the product selection screen,I choose MySQL Server and any additional components i needed.
6. **Configure MySQL Server**:I followed the installation wizard to configure MySQL Server. Set up a root password and other configuration settings as needed.
7. **Complete Installation**:Then proceeded with the installation process and let the installer complete the setup.
8. **Verify Installation**: After installation, I verified that MySQL is installed correctly by opening a Command Prompt and typing `mysql --version`.

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
