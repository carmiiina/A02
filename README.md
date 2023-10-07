<!DOCTYPE html>
<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8" />
    <h1>Tutorial: Using Git and GitHub</h1>
</head>
<body>
<h2>Introduction</h2>
GitHub is a freely accessible open-source version control system, employed for tracking alterations in source code and other documents. It enables multiple individuals to collaborate concurrently on a single document, with the added benefit of being able to revert to prior versions in the event of significant bugs. Linus Torvalds, the originator of Linux, is the mind behind its creation. - Intro To GitHub-2019
    
<h3>Table of Contents</h3>

    Installing Git
    Setting up Git
    Creating a Local Repository
    Making Changes
    Committing Changes
    Creating a GitHub Repository
    Pushing to GitHub
    Pulling Changes
    Branching and Merging
    Collaborating with Others

1. Installing Git <a name="installing-git"></a>
Download and install Git from the official website: Git Downloads

3. Setting up Git <a name="setting-up-git"></a>
Open a terminal or command prompt and set your username and email:
bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"

3. Creating a Local Repository <a name="creating-a-local-repository"></a>
    Create a new directory for your project: mkdir my_project
    Navigate into the directory: cd my_project
    Initialize a Git repository: git init

4. Making Changes <a name="making-changes"></a>
    Create or modify files in your project.
    Use git status to see which files have been modified.

5. Committing Changes <a name="committing-changes"></a>
    Add files to the staging area: git add filename or git add . to add all files.
    Commit changes: git commit -m "Descriptive commit message"

6. Creating a GitHub Repository <a name="creating-a-github-repository"></a>
    Go to GitHub and log in (or sign up).
    Click the "+" icon in the top right corner and select "New repository".
    Fill in the details, optionally add a .gitignore and license.
    Click "Create repository".

7. Pushing to GitHub <a name="pushing-to-github"></a>
    Copy the repository URL from GitHub.
    Add the remote repository: git remote add origin <repository_url>
    Push your local repository to GitHub: git push -u origin master

8. Pulling Changes <a name="pulling-changes"></a>

If someone else makes changes:
    Fetch changes from the remote repository: git fetch origin
    Merge the changes into your local branch: git merge origin/master

9. Branching and Merging <a name="branching-and-merging"></a>
    Create a new branch: git branch new_branch
    Switch to the new branch: git checkout new_branch
    Make changes, commit, and push as before.
    Merge branches: git checkout master then git merge new_branch

10. Collaborating with Others <a name="collaborating-with-others"></a>
    Add collaborators on GitHub in the repository settings.
    Collaborators clone the repository, make changes, commit, and push.

<h1>Conclusion</h1>

You now have a basic understanding of how to use Git and GitHub for version control. Keep practicing, and explore more advanced features as you become comfortable with the basics. Happy coding!


You must include definitions for the following terms in a separate list aside from your directions.
This will be like a glossary at the end of a text book.
<ul>
   <li><b>Branch</b></li>
        <dd>A branch in Git is a separate line of development that allows you to work on a specific feature or fix without affecting the main codebase. It enables multiple parallel streams of work.</dd>
    <li><b>Clone</b></li>
        <dd>Cloning in Git refers to creating a local copy of a remote repository (usually on GitHub) on your own machine. This allows you to work on the code locally.</dd>
    <li><b>Commit</b></li>
        <dd>A commit is a snapshot of the repository at a specific point in time. It records changes made to the repository and creates a unique identifier for that set of changes.</dd>
    <li><b>Fetch</b></li>
        <dd>Fetching in Git means downloading any changes from a remote repository to your local machine. It updates your local copy of the repository with the latest changes, but it does not integrate them with your current working branch.</dd>
    <li><b>GIT</b></li>
        <dd>Git is a distributed version control system used for tracking changes in source code during software development. It allows multiple contributors to collaborate on a project.</dd>
    <li><b>Github</b></li>
        <dd>GitHub is a web-based platform that provides Git repository hosting, collaborative tools, and various features for developers. It's widely used for version control and collaborative development.</dd>
    <li><b>Merge</b></li>
        <dd>Merging in Git is the process of integrating the changes from one branch into another. This combines the work done in different branches into a single branch, often the main branch.</dd>
    <li><b>Merge Conflict</b></li>
        <dd>A merge conflict occurs when Git is unable to automatically merge changes from different branches due to conflicting changes in the same lines of code. It requires manual resolution.</dd>
    <li><b>Push</b></li>
        <dd>Pushing in Git means uploading your local commits to a remote repository (like GitHub). This makes your local changes available to other collaborators.</dd>
    <li><b>Pull</b></li>
        <dd>Pulling in Git refers to fetching and then merging the changes from a remote repository into your local repository. It's a way to update your local repository with the latest changes from the remote.</dd>
    <li><b>Remote</b></li>
        <dd>A remote in Git refers to a repository hosted on a server (like GitHub) that's used for collaboration. It's a copy of the project that's hosted somewhere else.</dd>
    <li><b>Repository</b></li>
        <dd>A repository, often referred to as "repo," is a collection of files and version history managed by Git. It can be either local (on your computer) or remote (hosted on a server, like GitHub). It stores the entire project history.</dd>
</ul>
<h1>Resources</h1>
<ul>
    <li>IS 117 Powerpoint slide-Intro To GitHub-2019</li>
    <li>ChatGPT</li>
</ul>
</body>
</html> 
