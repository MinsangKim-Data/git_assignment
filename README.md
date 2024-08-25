# Git Assignment - <MinsangKim-Data>

a. What is an issue?

An issue is a feature in GitHub that allows you to track tasks, enhancements, bugs, and other kinds of requests for a repository. They overall help manage and organize tasks in a project environment. 

b. What is a pull request?

A pull request is a way for a contributor to request changes to a repository on GitHub, especially to a repository that they do not mainly own or are in charge of. So in this case, the contributor would submit their changes for review and the repository maintainers can oversee the changes.

c. Describe the steps to open a pull request?

1. If it is a repository you do not own, fork the repository to your own GitHub.
2. Clone the forked repository to your local machine.
3. Make the changes you wish to make in the local repository.
4. Commit and push the changes to the forked repository on your GitHub.
5. On GitHub, navigate to the original repository and click on "new pull request". 
6. Choose branch from your fork that contains your changes and submit the pull request for review. 

d. Describe the steps to add a collaborator to a repository (share write permissions)

1. go to the repository on GitHub.
2. Click on "settings" tab.
3. Select "collaborators" on the sidebar.
4. Click on "Add people".
5. Enter the people you wish to add with username, full name, or email.
6. click "Add collaborator" and the added person(s) will get an intivitation to join as a collaborator.

e. What is the difference between git and GitHub?

**Git** is a version control system that allows you to track changes in your files, manage project histories, and collaborate with others. This system operates on your local system/machine.

**Github** is a web-based platform that hosts Git repositories, which allows people from all around the world to contribute to Git projects and repositories online. It also has interesting, helpful features such as pull requests, issue tracking, and project management. 

f. What does git diff do?

**git diff** without any arguments, shows the differences between your working directory and the staging area (what has changed but not yet staged for commit) So in other words, it shows a readout of changes you have made but not yet staged using **'git add'**.

g. What is the main branch?
The main branch is the default or master branch that exists in the Git repository where the source code or stable code resides. It is usually the branch where the final version of the project is kept and from which releases are made. 

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

For good practice, it is not recommended to directly push changes directly into the main branch because unvetted changes my affect the main branch in unwanted ways, especially in group project settings. Instead, a new branch should be created that you can make your changes in. Then you can finally open a pull request to merge the changes into the main branch after some vetting process.