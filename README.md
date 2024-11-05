# Git-and-Github-Workshop-DRESTEIN-24
NAME: THAMIZHINI K 
REGISTER NUMBER : 24001836
DEPARTMENT : ECE
YEAR : 1st year  
                  Git and Github workshop assignment
1.	 Setup and Initialize: - What command do you use to create a new directory named `git-workshop` and navigate into it?
Ans:
                 mkdir git-workshop    - To Create the directory
      cd git-workshop       - To Navigate into the directory 

2.	Initialize a Git Repository: - What command initializes a Git repository in your directory?
Ans:
      Git init command initializes a git repository in your directory

3.	Create and Modify Files: - How do you create a new file named `hello.txt` and add the content 'Hello, Git Workshop!' to it using a single command?
Ans:
      echo "Hello, Git Workshop!" > hello.txt

4.	Check the Status of Your Repository: - What command displays the status of your repository?
Ans:
      git status

5.	Stage and Commit Changes: - What command stages the file `hello.txt`? - What command commits the staged file with the message 'Add hello.txt with welcome message'?
Ans: 
    git add hello.txt
    git commit -m "Add hello.txt with welcome message"

6.	. Branching: - What command creates a new branch named `update-content`? - How do you switch to the `update-content` branch?
Ans:
     git branch update-content
     git checkout update-content

7.	Make Changes on the Branch: - What command would you use to append the text 'This is a simple Git assignment.' to `hello.txt`?
- What command stages and commits the changes with the message 'Update hello.txt with additional message'?
Ans:
     echo "This is a simple Git assignment." >> hello.txt
git add hello.txt
git commit -m "Update hello.txt with additional message"
   
8.	Merge Changes: - What command switches you back to the `main` branch? - How do you merge the `update-content` branch into `main`?
Ans:
     git checkout main
     git merge update-content

9.	View Commit History: - What command shows the commit history?
Ans:
      git log

10.	  Undo and Reset (Practice Safely): - If you make a change to `hello.txt` that you want to revert before committing, what command would you use? - How can you reset your branch to a previous commit (optional, for advanced practice)?
Ans:
      git checkout -- hello.txt
   hard reset
       git reset --hard <commit-hash>

11.	 Push to a Remote Repository (Optional): - What command adds a remote repository named `origin`? - What command pushes your local `main` branch to the remote repository? 
Ans:
      git remote add origin <repository-url> 
      git push origin main

