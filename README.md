Here are the steps to initialize Git and push code to a GitHub repository:

    Install Git: If Git is not already installed on your computer, download and install it from the official Git website (https://git-scm.com/).

    Set Up Git: Open a terminal or command prompt and set up your Git username and email using the following commands: git config --global user.name "Your Name" ; git config --global user.email "your.email@example.com"

Create a GitHub Repository:

    Log in to your GitHub account.
    Click on the "New" button to create a new repository.
    Enter a repository name, choose visibility (public or private), and optionally add a README file or .gitignore file.
    Click on the "Create repository" button to create the repository.

Initialize Git in Your Local Project:

    Open a terminal or command prompt.
    Navigate to your project directory using the cd command.
    Initialize a new Git repository in your project directory using the following command: git init

Add and Commit Your Code: Add your files to the Git staging area using the git add command. For example, to add all files, use: git add .
Commit the changes to the repository with a descriptive commit message using the git commit command: git commit -m "Initial commit"

Link Your Local Repository to the GitHub Repository: Go to your GitHub repository and copy the repository URL (HTTPS or SSH).
    In your terminal, add the remote repository URL using the following command (replace <repository-url> with your actual repository URL): git remote add origin <repository-url>

Push Your Code to GitHub: Push your committed code to the GitHub repository using the git push command: git push -u origin master
        If prompted, enter your GitHub username and password or authentication token.
