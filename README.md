<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SmartBridge Testing Project</title>
</head>
<body>
    <h1>SmartBridge Testing Project</h1>

    <h2>Introduction</h2>
    <p>
        This repository contains the testing suite for the SmartBridge project. It includes automated test cases created using Katalon Studio and supports large file management with Git LFS.
    </p>

    <h2>Features</h2>
    <ul>
        <li><strong>Automated Test Cases:</strong> Designed to validate core functionalities.</li>
        <li><strong>Katalon Studio Integration:</strong> Seamless integration with Katalon Studio for test execution.</li>
        <li><strong>Large File Management:</strong> Utilizes Git LFS to handle large files efficiently.</li>
    </ul>

    <h2>Prerequisites</h2>
    <ul>
        <li><strong>Git:</strong> Ensure that Git is installed on your system.</li>
        <li><strong>Katalon Studio:</strong> Download and install from <a href="https://www.katalon.com/" target="_blank">Katalon’s website</a>.</li>
        <li><strong>Git LFS:</strong> Install Git LFS to manage large files.
            <pre><code>git lfs install</code></pre>
        </li>
    </ul>

    <h2>Installation</h2>

    <h3>Cloning the Repository</h3>
    <ol>
        <li>Clone the repository:
            <pre><code>git clone https://github.com/Eswaran-IT/SmartBridge_Testing_Project.git</code></pre>
        </li>
        <li>Change to the project directory:
            <pre><code>cd SmartBridge_Testing_Project</code></pre>
        </li>
    </ol>

    <h3>Configuring Git LFS</h3>
    <ol>
        <li>Track large files (if applicable):
            <pre><code>git lfs track "*.largefileextension"  # Replace with actual extensions</code></pre>
        </li>
    </ol>

    <h3>Importing into Katalon Studio</h3>
    <ol>
        <li>Open Katalon Studio.</li>
        <li>Go to <strong>File</strong> > <strong>Import</strong> > <strong>Katalon Studio Project</strong>.</li>
        <li>Select the project directory and import it.</li>
    </ol>

    <h2>Running Tests</h2>
    <ol>
        <li><strong>Open Katalon Studio:</strong> Launch the application and open the imported project.</li>
        <li><strong>Execute Test Cases:</strong>
            <ul>
                <li>Navigate to the <strong>Test Cases</strong> folder in the project explorer.</li>
                <li>Right-click on a test case and select <strong>Run</strong>.</li>
                <li>Alternatively, use the <strong>Run</strong> button in the toolbar to run all test cases.</li>
            </ul>
        </li>
    </ol>

    <h2>Contributing</h2>
    <ol>
        <li><strong>Fork the Repository:</strong> Create a personal copy of the repository.</li>
        <li><strong>Create a Branch:</strong>
            <pre><code>git checkout -b feature-branch</code></pre>
        </li>
        <li><strong>Make Changes:</strong> Implement your changes.</li>
        <li><strong>Commit Changes:</strong>
            <pre><code>git commit -am 'Add new feature'</code></pre>
        </li>
        <li><strong>Push Changes:</strong>
            <pre><code>git push origin feature-branch</code></pre>
        </li>
        <li><strong>Open a Pull Request:</strong> Submit your changes for review.</li>
    </ol>

    <h2>License</h2>
    <p>
        This project is licensed under the MIT License. See the <a href="LICENSE" target="_blank">LICENSE</a> file for more details.
    </p>

    <h2>Contact</h2>
    <p>
        For questions or feedback, reach out to <a href="mailto:your-email@example.com">your-email@example.com</a>.
    </p>
</body>
</html>
