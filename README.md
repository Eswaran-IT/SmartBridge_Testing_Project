SmartBridge Testing Project
Overview
This repository contains an automated testing suite for the SmartBridge project, utilizing Katalon Studio. It includes a range of test cases designed to validate core functionalities. The project also supports large file management with Git LFS.

Features
Automated Test Cases: Comprehensive scripts for testing application features.
Katalon Studio Integration: Full compatibility with Katalon Studio for executing tests.
Large File Management: Uses Git LFS to handle large files effectively.
Getting Started
Prerequisites
Git: Ensure Git is installed on your system.
Katalon Studio: Download and install Katalon Studio from Katalon’s website.
Git LFS: Install Git LFS for managing large files.
sh
Copy code
git lfs install
Clone the Repository
Clone the repository to your local machine:
sh
Copy code
git clone https://github.com/Eswaran-IT/SmartBridge_Testing_Project.git
Navigate to the project directory:
sh
Copy code
cd SmartBridge_Testing_Project
Setup
Install Dependencies: If there are any specific dependencies for Katalon Studio, follow their installation instructions.

Configure Git LFS (if applicable):

sh
Copy code
git lfs track "*.largefileextension"  # Replace with actual file extensions if needed
Import into Katalon Studio:

Open Katalon Studio.
Go to File > Import > Katalon Studio Project.
Select the project directory you cloned and import it.
Running Tests
Open Katalon Studio: Launch Katalon Studio and open the imported project.
Execute Test Cases:
Navigate to the Test Cases folder in the Katalon Studio project explorer.
Right-click on the test case you want to run and select Run.
Alternatively, use the Run button in the toolbar to execute all test cases.
