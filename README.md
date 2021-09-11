### 1. Create a repository named as “Assignment 2” in github with Readme.md file, Questions must be paste in the readme file.

### 2. Clone your repository.
    $ git clone https://github.com/Shashintha95/Assignment2.git
    Cloning into 'Assignment2'...
    remote: Enumerating objects: 3, done.
    remote: Counting objects: 100% (3/3), done.
    remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
    Receiving objects: 100% (3/3), done.
    
### 3. Add the text file that should have the answer of Q1.
    $ git add Q1.txt
    
### 4. Add another file to do the following.
    $ touch anotherfile.txt
    
### 5. Create another branch .
    $ git checkout -b anotherBranch
    Switched to a new branch 'anotherBranch'
    
### 6. Make changes to your files.

### 7. see if the file change is detected with git status.
    $ git status
    On branch anotherBranch
    Changes to be committed:
      (use "git restore --staged <file>..." to unstage)
            new file:   Q1.txt

    Untracked files:
      (use "git add <file>..." to include in what will be committed)
            anotherfile.txt
           
### 8. stage the changes with git add .

     $ git add .
     
### 9. check that the add did what you expected with git status.

    $ git status
    On branch anotherBranch
    Changes to be committed:
      (use "git restore --staged <file>..." to unstage)
            new file:   Q1.txt
            new file:   anotherfile.txt
            
### 10. make the commit with git commit.

    $ git commit
    Aborting commit due to empty commit message.





