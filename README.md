# Github Tutorial 

This is a tutorial on the basic functionality of github using the command line.

To use git on a mac, the easiest way to install is by installing [xcode command line tools](http://osxdaily.com/2014/02/12/install-command-line-tools-mac-os-x/).

On linux, you can install by running 
```$ sudo apt-get install git-all```
from the terminal. 

Windows users can install git [here](http://git-scm.com/download/win ) and can use it through the command prompt. 

Full install instructions can be found [here.](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

## Git Basics 
### Create a Repository 

https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/

### Cloning a Repository 

To clone this repository, type 
```shell
git clone https://github.com/geebioso/Git-Tutorial
```

### Basic Commands

```git status```: shows tracked and untracked files and which files are behind the latest commit     
```git add [file]```: adds a file to be committed     
```git reset [file]```: resets a file that was added to be commited     
```git commit -m [message]```: commits all files that were added     
```git push```: pushes the latest commit to the remote repository     
```git log --oneline```: shows you your history of commits     

## Branches 

```git branch```: gives a list of available branches and which branch you are in     
```git checkout -b [branchname]```: checks out a branch     
```git pull origin master```: merges your local branch with code on master ([advanced reading](http://longair.net/blog/2009/04/16/git-fetch-and-merge/))     
```git pull```: pulls the latest changes from your remote branch     

After checking out a branch, you can add files, commit and push to that branch. To commit changes to master, intiate a [pull request](https://help.github.com/articles/about-pull-requests/). To switch branches back to master, type `git checkout master`.

## Extras
### Add a Collaborator 

You can [add a collaborator](https://help.github.com/articles/inviting-collaborators-to-a-personal-repository/) who will be able to push edits to your remote repository. 
### Issues 
In collaborative projects, [issues](https://guides.github.com/features/issues/) are a great way to check each others code and keep track of updates that need to be made. 

### Documentation

To find documentation on any git command, type
```git --help [command]```

### Tutorials 
**Git Tags**: http://alblue.bandlem.com/2011/04/git-tip-of-week-tags.html    
**Undoing changes**: https://www.atlassian.com/git/tutorials/undoing-changes/git-revert    
**Git stash**: https://www.atlassian.com/git/tutorials/git-stash    
**Resolving Conflicts**: https://githowto.com/resolving_conflicts, https://easyengine.io/tutorials/git/git-resolve-merge-conflicts/

### .git Directory 

You can view how git is tracking changes in the .git directory in your [git repository](https://githowto.com/git_internals_git_directory). If you remove the .git directory, your local directory will no longer be a repository. 

### Git Pages 
You can use [git pages](https://pages.github.com/) to host a website. The basic idea is you initialize a git repository with an index.html file that contains your html code. For example my directory `geebioso` links to geebioso.github.io. A good example is [colah.github.io](http://colah.github.io/). 

