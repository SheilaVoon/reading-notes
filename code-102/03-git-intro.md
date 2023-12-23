# Git Intro

## 1. What is Version Control?

* Version control is a system for managing changes to files over time. It's like a timeline for your code, allowing you to:
  * Track every modification made to files
  * Revert to previous versions if needed
  * Compare different versions to see what's changed
  * Collaborate with others effectively
  * Maintain a history of project development

## 2. What is cloning in Git?

* Cloning is the process of creating a local copy of a remote Git repository on your computer. It's like downloading a project's entire codebase, including its history of changes.

* The command to clone a repository is:

```git clone <repository_url>```

## 3. What is the command to track and stage files?

* Tracking files means telling Git to start monitoring them for changes.
* Staging files means preparing those changes to be included in a commit.
* The commands for tracking and staging are:

```text
git add <file1> <file2>         # Add specific files to the staging area
git add .                       # Add all modified files to the staging area
```

## 4. What is the command to take a snapshot of your changed files?

* Taking a snapshot in Git means creating a commit, which is a saved point in the project's history.
* The command to create a commit is:

```text
git commit -m "Your commit message"
```

## 5. What is the command to send your changed files to GitHub?

* Sending your changes to GitHub means pushing commits from your local repository to a remote repository on GitHub.
* The command to push your changes is:

```text
git push origin <branch_name>
```

(where ```origin``` is typically the name of the remote repository and branch_name is the name of the branch you want to push to)
