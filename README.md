# Git Assignment - renrihui8415
a. What is an issue?
- In GitHub, an issue refers to a task, bug or feature request recorded within a repository's issue tracking system to plan, discuss and track work. Issues typically contain information such as a title, description, labels, assignees and comments. It serves a organizational role in software development workflows. Pull requests (PRs) are often linked to specific issues, which ensures transparency, traceability, and alignment development tasks and code changes.

b. What is a pull request?
- A pull request (PR) is a proposal to merge a set of changes from one branch into another. In a pull request, collaborators can review and discuss the proposed set of changes before they integrate the changes into the main codebase. In the current software development landscape, adopting automated processes, including integrating PRs with CI/CD pipelines, is recognized as a leading approach within the data science domain.

c. How do I open up a pull request?
- To open a pull request:
  1. Push your changes to a branch in your repository
  2. Navigate to your repository on GitHub.com
  3. In the "Branch" menu, choose the branch that contains your commits.
  4. Click Compare & pull request to create a pull request.
  5. Select the branch with your changes as the "compare" branch and the branch you'd like to merge into as the "base" branch.
  6. Review the changes, add a title and description, and click "Create pull request".

d. Give me a step by step guide on how to add someone to your repository.
- To add someone to your repository:
  1. Navigate to your repository on GitHub.com
  2. Go to the "Settings" tab.
  3. Click on "Collaborators" or a similar button. GitHub may require confirmation when accessing sensitive features.
  4. Click "Add people".
  5. Enter the username, email, or name of the person you'd like to add as a collaborator. Then click a name in the list of matches.
  6. Click "Add NAME/EMAIL to this repository".
  7. The person will receive an email inviting them to the repository. Once they accept your invitation, they will have collaborator access to your repository.
  
e. What is the difference between git and GitHub?
- Git is a distributed version control system used for tracking changes in source code during software development. GitHub is a platform built on top of Git that provides hosting for Git repositories, along with collaboration features such as issue tracking, pull requests, and code review. Git can be used entirely locally on your computer without an internet connection. GitHub, being a web-based platform, requires an internet connection to access its features and repositories. Git and GitHub are closely related. Git decentralizes version control, enabling individual developers to work independently, while GitHub centralizes collaboration enabling seamless teamwork and efficient software development.

f. What does git diff do?
- 'git diff' is a Git command that shows the difference between changes. It compares files line by line and displays the added, modified, and deleted lines. 
  1. When you run 'git diff' without any additional arguments, it shows the differences between the files in your working directory and the files in the staging area. This comparison helps you to see the changes you've made to your files since the last 'git add' command.
  2. If you've already staged changes with 'git add', you can use 'git diff --staged' or 'git diff --cached' to review the changes that are about to be committed, helping you ensure that you're only committing the intended modifications.

g. What is the main branch?
- The main branch (formerly named 'master') in a Git repository is the primary branch that typically represents the latest stable version of the project. It often serves as the default branch from which releases are made. The trend of transitioning from 'master' to 'main' or 'default' branch names reflects a desire to align terminology with the collaborative nature of version control, fostering a more welcoming environment for all contributors.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
- It's generally not recommended to push changes directly to the main branch, especially in collaborative environments. As the main branch is critical to the project, it is often protected from direct pushes or force pushes to prevent accidental changes or disruptions. It's a best practice to create a new branch for each feature or bug fix, make changes on that branch, open a pull request for review, discussion and testing, and then merge those changes into the main branch.
