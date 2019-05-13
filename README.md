# Erst Cheat Sheet

## Git

### init

The git init command creates a new Git repository. It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository. Most other Git commands are not available outside of an initialized repository, so this is usually the first command you'll run in a new project.

```bash
git init
```

### clone
Git clone is a Git command line utility which is used to target an existing repository and create a clone, or copy of the target repository. Cloning a local or remote repository. Cloning a bare repository. Using shallow options to partially clone repositories. Git URL syntax and supported protocols

### pull

Will do 2 thigs.
- Will do a git fetch
- Will do a git merge.

### commit

Bo add information

Will commit you're change to you're local or remote git repo / branche.

### status
Bo add information

Gives you the local git repo, status. Will show you if you have Ex. any files of commits waiting to be made. 

### fetch
Christian add information

Download the Remote repo, branche histrory to local Git Repo.

### mearge
Christian add information

When you hava a brance out from another branche or master, you need to merge thoes to, togerther at times. That you do with this command.

### rm
Remove a file from the Index file. When you use git add [Filename] you add a file of folder to the Index. As in you stage a file.

### branch

Used to create and or delete a brance. But not the only way to delete a branche.

### checkout

Change branche in Git. Default you're in master. If you have multibol branches, you need to change between them by using Git Checkout [branch name]

### ???

## Terraform

### init

Used to Pre a working dir for use with Terraform. If any changes are made, you will need to run Terraform init to update the working folder to latest config.

### plan

Terraform Plan is used to try run the code you wrote. It will show you what will go currect, and what errors will arise. You can allso build you're plan in to a file, so you will be able to process it later. It's in many ways, if not all the same as using -whatif in MS Powershel.

### console

When you need to try out some functions or kode lines in Terraform, you can use the Terraform console. It will process it and give you a better feeling of what is happning.