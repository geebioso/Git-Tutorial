# Github Tutorial 

This is a tutorial on the basic functionality of github using the command line.

To use git on a mac, the easiest way to install is by installing xcode command line tools. 

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

## Branches 

```git branch```: gives a list of available branches and which branch you are in     
```git checkout -b [branchname]```: checks out a branch     
```git pull origin master```: merges your local branch with code on master ([advanced reading](http://longair.net/blog/2009/04/16/git-fetch-and-merge/))     
```git pull```: pulls the latest changes from your remote branch     

After checking out a branch, you can add files, commit and push to that branch. To commit changes to master, intiate a [pull request](https://help.github.com/articles/about-pull-requests/). To switch branches back to master, type `git checkout master`.

## Extras
### Git Documentation

To find documentation on any git command, type
```git --help [command]```

### Git Directory 

You can view how git is tracking changes in the .git directory in your [git repository](https://githowto.com/git_internals_git_directory). If you remove the .git directory, your local directory will no longer be a repository. 


### Git Pages 

You can use [git pages](https://pages.github.com/) to host a website. The basic idea is you initialize a git repository with an index.html file that contains your html code. For example my directory `geebioso` links to geebioso.github.io. A good example is [colah.github.io](http://colah.github.io/). 


added some code
