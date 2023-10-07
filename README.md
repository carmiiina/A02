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
<o1>
<li>Installing Git</li>
<li>Setting up Git</li>
<li>Creating a Local Repository</li>
<li>Making Changes</li>
<li>Committing Changes</li>
<li>Creating a GitHub Repository</li>
<li>Pushing to GitHub</li>
<li>Pulling Changes</li>
<li>Branching and Merging</li>
<li>Collaborating with Others</li>
</o1>
<dl>    
<dt><b>1. Installing Git</b></dt>
<dd>Download and install Git from the official website: <a href="https://git-scm.com">Git Downloads</a></dd>

<dt><b>2. Setting up Git</b></dt>
<dd>Open a terminal or command prompt and set your username and email:</dd>
<p><dd>"Your Name"</dd></p>
<p><dd>"youremail@example.com"</dd></p>

<dt><b>3. Creating a Local Repository</b></dt>
<dd>Create a new directory for your project, and then navigate into the directory. Initialize a Git repository.</dd>

<dt><b>4. Making Changes</b></dt>
<dd>Create or modify files in your project.
Use git status to see which files have been modified.</dd>
    
<dt><b>5. Committing Changes</b></dt>
<dd>Add files to the staging area: git add filename or git add . to add all files.
Commit changes: git commit -m "Descriptive commit message"</dd>

<dt><b>6. Creating a GitHub Repository</b></dt>
<dd>Go to GitHub and log in (or sign up).
Click the "+" icon in the top right corner and select "New repository".
Fill in the details, optionally add a .gitignore and license.
Click "Create repository".</dd>

<dt><b>7. Pushing to GitHub</b></dt>
<dd>Copy the repository URL from GitHub.
Add the remote repository: git remote add origin <repository_url>
Push your local repository to GitHubr</dd>
    
<dt><b>8. Pulling Changes</b></dt>
<dd>If someone else makes changes:

Fetch changes from the remote repository: git fetch origin
Merge the changes into your local branch: git merge origin/master</dd>

<dt><b>9. Branching and Merging</b></dt>
<dd>Create a new branch: git branch new_branch
Switch to the new branch: git checkout new_branch
Make changes, commit, and push as before.
Merge branches: git checkout master then git merge new_branch</dd>

<dt><b>10. Collaborating with Others</b></dt>
<dd>Add collaborators on GitHub in the repository settings.
Collaborators clone the repository, make changes, commit, and push.</dd>
</dl>
</body>
<body>
<h1>Glossary</h1>
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
