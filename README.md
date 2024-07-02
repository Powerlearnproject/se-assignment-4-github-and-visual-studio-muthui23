[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/GvXCZgfk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15337520&assignment_repo_type=AssignmentRepo)
# SE-Assignment-4
Assignment: GitHub and Visual Studio
Instructions:
Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.

Questions:
Introduction to GitHub:
What is GitHub, and what are its primary functions and features? Explain how it supports collaborative software development.
GitHub is a web-based platform that uses Git, the distributed version control system, to help developers manage and collaborate on software projects.
It supports collaborative software development by ;
Sharing of repositories(repos)
Branching and merging codes.
Pull requests and review tools.
Open source contributions for everyone.

functions and features:
Version control where Git is used allowing tracking of code and managing of branches.
Repo is a place where files are stored.
Collaboration works by use of forking ,which creates a bcopy of the repo to their account.
pull requests let developer propose change to a codebase.
Project management:
Issues is a tool for tracking bugs and enhancements .
Projects is a board that organizes issues and pull requests, showing an overall view of the progress in the project.
Documentation:
README files provide overview ,install instructions and uder guides ..etc.
Community:
Contributions show the contributions over time and promotes community involvent.
Users can also star repositories to show interest and follow other developers.



Repositories on GitHub:
What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it.
A repository is a central place where all files of a project are stored including its revision history.

Creating a new repository:
Sign in to github.
Click on plus sign and select new repository.
Fill in the repository details like the name and its description.
Initialize by adding a README file, .gitignore and choosing a license.

Elements of a repository:
README file : provides overview
LICENSE file : shows how others can use and modify your code.
.gitignore: list files and directories to ig nore ie temporary files.
Documrntation that provides all information about the project.
Source code which are the actual code files of the project.
Tests of the project.
Changelog.


Version Control with Git:
Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers?
Version control is a system that records changes to files over time so one can recall specific versions later.
Github enhances version control by :
Pull requests which allow developersto discuss code changes before merging them to the main branch.
Github is a central place where developers can push and pull code.
Forking:developers can create personal copies where they can make changes without changing the actual project.
Github actions allow running tests and deploying code whenever cahnges are pushed.
Wikis make sure the documentation is comprehensive.
Githubs has a user friendly interface where people can access everything especially those who arent comfortable with the command line.


Branching and Merging in GitHub:

What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes, and merging it back into the main branch.
Branches allow developers to create separate line of development.Its used to experiment new ideas and fixing bugs without affecting main codebase.

Creating a branch:
1.Ensure you are on the main branch.ie git checkout main
2.Pull the changes ie git pull origin
3.Create new branch using the git branch command.
4.USe git checkout to switch to new branch.
5.Make changes to your files.
6.Stage the changes ;git add .
7.Commit the changes.
8.Switch to the main branch again.
9.Pull the latest changes.
10.Use git merge to merge the new branch to main branch.
Resolve conflicts if any and push the merged changes back to the repository.

 

Pull Requests and Code Reviews:
What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to create and review a pull request.
A pull request is used by a developer to notify team members of a completed feature or a  bug has been fixed.
Pull requests facilitate reviews by allowing others to see, comment and discuss changes before they are included.They also keep record of changes.

Creating a pull request:
Git push origin new_feature
Go to the repo where you pushed the branch.
Open pull request and fill out the pull request form.
Create pull request by clicking the button.
Reviewing the pull request:
Go to pull requests tab.
Examine the changes and leave comments on some lines,.
Request or approve changes.
Merge the pull request.



GitHub Actions:
Explain what GitHub Actions are and how they can be used to automate workflows . Provide an example of a simple CI/CD pipeline using GitHub Actions.
Github actions is a CI/CD service that allows one to automate workflows within GitHub.
One can build,test and deploy your code from Github.

CI/CD pipeline:
Create a workflow file.
Define the workflow ie name 
                       trigger events
                        jobs section :build and deploy
                        build job     
                        Deploy job


Introduction to Visual Studio:
What is Visual Studio, and what are its key features? How does it differ from Visual Studio Code?
Visual studio is a unified development environment(IDE)while vs code is a sophisticated text editor.
Visual studio includes comilers, code completion tools, source control extensions .


Integrating GitHub with Visual Studio:
Describe the steps to integrate a GitHub repository with Visual Studio. How does this integration enhance the development workflow?
Launch visual studio 
Go to file account settings add an account and select github.
Sign in with your GitHub credentials.
After the password a Success! message should be visible.
Ensure the github extension for visual studio is installed.

Intergration with github makes it easier to collaborate and one can commit, pull and sync changes without leaving visual studio.
Time is more efficient.



Debugging in Visual Studio:
Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?

Debugging tools:
Breakpoints interrupt a code execution .
Watch windows monitor variables and expressions .
Call stack displays sequence of function calls that led to the current point in code execution.
Output window.Display program output, debugging messages, and other information from the build and debug processes.
IntelliTrace
Record and replay the history of code execution to diagnose issues that are difficult to reproduce.
Diagnostic tools ie cpu usage and memory usage.



Collaborative Development using GitHub and Visual Studio:
Discuss how GitHub and Visual Studio can be used together to support collaborative development. Provide a real-world example of a project that benefits from this integration.
Using version control
collaboration tools such as live share and github discussions.
Code collaborations using pull requests and code ereview tools.
GitHub issues and project management.

One real-world example of a project benefiting from this integration is a web application development project. Let's consider a team building an e-commerce platform using ASP.NET Core in Visual Studio and hosting the code on GitHub.
Version Control: Developers can work on different features or bug fixes in Visual Studio and seamlessly commit their changes to GitHub, allowing for easy collaboration and tracking of code modifications.
Code Review: When a developer completes a feature, they can create a pull request on GitHub. Other team members can review the code changes, provide feedback, and suggest improvements, all within the GitHub interface.
Issue Tracking: The team can use GitHub's issue tracking system to manage tasks and bugs. These issues can be linked to the code in Visual Studio, providing a seamless workflow for issue resolution.
Continuous Integration: Visual Studio can be configured to trigger GitHub Actions for automated testing and deployment, ensuring that new code changes are thoroughly tested before being merged into the main branch.



Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
