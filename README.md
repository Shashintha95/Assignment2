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
   
### 11. Write a meaningful commit message (e.g. "Answers question 1").

    $ git commit -am "Answer Question"
    [anotherBranch 44b6813] Answer Question
     2 files changed, 1 insertion(+)
     create mode 100644 Q1.txt
     create mode 100644 anotherfile.txt
     
### 12. check that your working directory is clean with git status.

    $ git status
    On branch anotherBranch
    nothing to commit, working tree clean
    
### 13. check that your commit succeeded as expected with git log

    Author: shashi <shashijana48@gmail.com>
    Date:   Sun Sep 12 01:07:19 2021 +0700

        Answer Question

    commit 0f5a325d1f46bae91f1bd0150f3902d911d223f2 (origin/main, origin/HEAD, main)
    Author: Shashintha95 <85413556+Shashintha95@users.noreply.github.com>
    Date:   Sat Sep 11 16:07:06 2021 +0700

        Initial commit
        
        
### 14. Push your code up to a github repository


    $ git push origin anotherBranch
    Enumerating objects: 7, done.
    Counting objects: 100% (7/7), done.
    Delta compression using up to 4 threads
    Compressing objects: 100% (4/4), done.
    Writing objects: 100% (7/7), 964 bytes | 482.00 KiB/s, done.
    Total 7 (delta 0), reused 3 (delta 0), pack-reused 0
    remote:
    remote: Create a pull request for 'anotherBranch' on GitHub by visiting:
    remote:      https://github.com/Shashintha95/Assignment2/pull/new/anotherBranch
    remote:
    To https://github.com/Shashintha95/Assignment2.git
     * [new branch]      anotherBranch -> anotherBranch











