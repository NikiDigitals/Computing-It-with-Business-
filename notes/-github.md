- Course/Module/Topic:The Git & Github Bootcamp
  Issuer: Udemy  
  Lesson: -  
  Date: 2025-09-05
  Type: note  
  Tags: #Github #Git
  Related Project(s)  
  Related journals:

---

## Overview

Using Git and GitHub is part of a standard skill set every person working in IT should know.

- Git core (Committing, Branching and Merging, Diffing, Stashing, and undoing changes)
- Github - collab core (Fetching & pulling, Odds & Ends, Collaborative workflows)
- Git extras (Rebashing, Tags, Reflogs, Aliases)

## keyconcepts

<b>Git</B> is a Version control system (VCS) to:

- Track changes across files
- version control - Compare versions of a project
- Go back to older versions of a project and refer to them if needed.
- Collaborate and share changes with others
- Combine changes.

<b>Github</b> is a service that hosts Git repositories in the cloud, making it easier to collaborate with other people.
- The online platform for sharing work done on Git.   

- A <b>repository</b> is a directory with its own history
- <b>Github</b> is a service that hosts Git repositories in the cloud, making it easier to collaborate with other people.
  The online platform for sharing work done on Git.
- With the commands `git add` and `git commit`, you can save changes from different files in specific groups as a reference point.   
  
<b>Commit messages</b>
- Try to keep every commit about '1' thing. Remember, it needs to be clear to anyone what was changed!!!!
-  Use the present tense imperative style or whatever is normal in your organisation.
-  Sometimes the message needs to be longer than just a single line. Use the editor to do this. Make sure the first line is a summary.
-  When you forgot a file or need to fix the last commit message, you can amend Commits with `--amend`

### .Gitignore
When working on a project, you may want to ignore specific files in Git.
Examples of files you never want to commit include:
- Secrets, API keys, credentials, etc
- operating files
- Log files
- Dependencies & packaging




## Definitions/Syntax

`git status` gives you feedback on the status of the repository.   
`git init <Name of repository>` Create a new repository in your current directory.   
`git add <file names>` to state the files ready to commit and save them in the repository.   
`git .` to commit all files at the same time.   
`git commit -m "commit message"`   
`git commit' to commit and open an editor to record the message.
`git commit --amend` redo the last commit to fix an error in the message or add forgotten files.   
'git log' gives the log of all the commits in the repo.
`git log --oneline` makes the logs easier to look at with 1 log per line.  



## external resources
[Git documentation](https://git-scm.com/doc)   
[.gitignore file](toptal.com/developers/gitignore) generator to Create a start gitignore fi;e for specific projects
