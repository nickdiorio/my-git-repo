# Git and Github:

## Basic Git via the command line:
1. Download git: https://git-scm.com/ and run the installer with the default components selected and just step through the installation.  This means you don't need to change any of the options or selections.
2. Full reference available: https://git-scm.com/book/en/v2

### Configuring your environment
Open the git bash and type:

```
git config --global user.name "Your Name"
git config --global user.email your.email@example.com
```

### Checking out an exisiting repository
To get started with an existing repository, navigate within the git bash to the folder you want to check out to, e.g:

``` 
cd /c/projects/
```

On GitHub, navigate to the main page of the repository, and under the repository name, click **Clone or download**.  In the Clone with HTTPs section, click to copy the clone URL for the repo.  Then execute the clone command within Git Bash by pasting the URL you cpied after the git clone command, i.e:

```
git clone https://github.com/nickdiorio/my-git-repo.git
```

### Making modifications
As you add and modify files within your project, you can see the status of your repo at any time:

``` 
git status
```

This will tell you which files have been modified, and which files are new and not being tracked.

### Adding files to the staging area
For new files you create, you need to tell Git that you want to explicitly add them to version control.  The staging area is basically a place where you stage files before committing them.  It guarantees that you commit only exactly the files that you want in a particular commit.

```
git add orange.html
```

### Committing files
After you've added all the files you want to add to a particular commit, you commit them with a helpful message about what the commit contains.  Commits should contain logical partitions of work that make is easy to look at the log and understand what each commit was for.

```
git commit -m "Adding a webpage about the color orange"
```

### Pushing the commit to the remo repo
So, you've staged files, and committed them.  But now, you've finally got to push them out to remote repo so that everyone else working on the repo knows about your work and can ingest it into their own working copy.  To do this requires write access on the repo you are trying to push to, and you may be prompted for your username and password for github.

``` 
git push
```

## Getting started with Github desktop interface
1. Download Github for Windows: https://desktop.github.com/
