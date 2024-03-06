## Setup your local environment to start using Git  

 ### 1. Check Git Installation.  
 + Verify **Git** installation by typing '**git version**' in the command line.
        
### 2. Install Git  
+ Download **Git** from **Git Website** [Link](https://git-scm.com/downloads)  
+ On **Mac**, use Homebrew or MacPorts. 
+ On **Windows**, download the Git for Windows installer.
+ On **Linux**, use package managers like apt-get or yum/dnf.  

### 3. Command Line Basics  

+ Familiarize  with basic command line commands:   
   1. pwd  
   2. mkdir
   3. ls  
   4. cd  
   5. touch  
    
### 4. Create a Git Repository
 + Use '**git init**' to initialize a new repository in a directory.
 + Optionally, change the default branch from 'master' to 'main' using  
  '**git branch -m main**'.  

### 5. Git Repository Structure  
+ The repository is stored in the '**.git**' directory.
        
### 6. Git Status  
+ Use '**git status**' to check the status of the repository.  
+ It indicates the current branch, commits, and changes in the   working/staging area.  
### 7. Setting Git Configurations  
+ Git configurations are set at three levels :  
  1. System  
  2. Global  
  3. Local  
+ Required configurations:  
  1. user.name  (**git config --global user.name "Santhosh"**) 
  2. user.email (**git config --global user.email "S@gmail.com"**) for commit identification.  
  3. Change default branch name (optional) globally using '**git config --global init.defaultBranch main**'.  

+ View configurations with command '**git config --global --list**'.  
+ Remove configurations with command '**git config --global --unset**'.