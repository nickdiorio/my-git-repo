# Git and Github:

## Getting started with Git via the command line:
1. Download git: https://git-scm.com/ and run the installer with the default components selected and just step through the installation.  This means you don't need to change any of the options or selections.
2. Full reference available: https://git-scm.com/book/en/v2
3. Download Github for Windows: https://desktop.github.com/

## Configuring your environment
Open the git bash and type:

```
git config --global user.name "Your Name"
git config --global user.email your.email@example.com
```

## Checking out an exisiting repository
To get started with an existing repository, navigate within the git bash to the folder you want to check out to, e.g:

``` 
cd /c/projects/
```

On GitHub, navigate to the main page of the repository, and under the repository name, click **Clone or download**.  In the Clone with HTTPs section, click to copy the clone URL for the repo.  Then execute the clone command within Git Bash by pasting the URL you cpied after the git clone command, i.e:

```
git clone https://github.com/nickdiorio/my-git-repo.git
```

