1. Create a git repository “YourName_GitAndGithub” to your GitHub account and make it public.
Ans:
    a. Go to Github and create a new repository as "Mazharul_GitAndGitHUb"
    b. Make sure to check "Public" button while creating the repo


2. Clone this repository to your local machine.
Ans:
    a. Copy the HTTPS from local GitHub repo
    b. command: cd guthubquiz, to go inside the repo, from local machine
    c. command: git clone "https://github.com/mazharulboni/Mazharul_GitAndGithub-.git", enter, file should be cloned

3. Check which branch you are in now. Is it the “Master” branch?
Ans: Command: cd Mazharul_GitAndGithub-.git
		I am in main branch

4. Add two text files in this “Master” branch. 1. Git. text 2. GitHub.text
Ans.
    Command: touch git.txt github.txt

5. Write something about git and GitHub (at least 100 words) in the respective .text file.
Ans:
    Command: nano git.txt, Write 100 words about git, ctrl+x, y, enter
    Command: nano github.txt, Write 100 words about github, ctrl+x, y, enter


6. Add a README.md file. write the uses git commands, usage, and answers which you have finished.
Ans:
    Command: touch README.md
    Command: nano README.md, save the answer, ctrl+x, y, enter

7. See the changes by the respective git command.
Ans:	
    Command: git status

8. Now Push your Changes to remote. and check the remote changes.
Ans:
       command: git status, to see if the file ready/need to be add
       command: git add ., to add the files to git
       command: git commit -m "any message", to commit the file
       command: git push 

9. Add a “temp” folder in the local directory. and some files(image, video) to that folder.
Ans:
    command: mkdir temp
    Command: cp Pictures/image temp/
    Command: cp Videos/video temp/

10. Add a “.gitignore” file to your local directory.
Ans:
    command: touch .gitignore, from the temp directory

11. Declare the “temp” folder in the “.gitignore” file because you don’t want to store these files in the remote repository.
Ans:
    Command: nano .gitignore
            Declare in the text editor to ignore this file

12. See the local changes by the respective git command.
Ans:
     Command: git status


13. Now-Again push all the changes to the remote repository.
Ans:
    Command: git add .
    command: git commit -m "any message", to commit the file
    command: git push -u origin main https://github.com/mazharulboni/Mazharul_GitAndGithub-.git

14. Add a feature branch “differences” to your repository. Check how many branches you have now. then set your current branch as the “differences” branch.
Ans:
    	command: cd boni_GitAndGithub
	command: git branch differences
    	Two branches now, main and differences
	To set my current branch as the “differences” branch  "git checkout differences".

15. Update the text files (1. Git. text 2. GitHub.text) by writing the features of git and GitHub
Ans:
    command: nano git.txt, make necessary changes, save the changes.
    command: nano github.txt, make necessary changes, save the changes.


16. Adds one more file “difference. text”. write differences between git and GitHub on that file.
Ans:
    command: touch differences.txt
    command: nano differences.txt, edit and save the change


17. Update the README.md file. write the uses git commands, usage, and answers which you have finished.
Ans:
    nano README.md
    Copy and paste te answer


18. See the changes by the respective git command.
Ans:
    git status

19. Push all the changes to the remote.
    Command: git add .
    command: git commit -m "any message", to commit the file
    command: git push --set-upstream origin differences


20. Do you see any changes between your two branches?
Ans:
    Yes I do

21. Set your current branch as the “Master” Branch. and merge with the feature branch (“differences”).  (After this step it's little advance for you at this stage of the course, but you can try.)
Ans:
    I switched the main branch as default branch
	command: git checkout main
	command: git add .


22. Do you see any changes between your two branches?
Ans:
    I see no changes as feature and main branches are merged

23. Push all the changes to the remote.
Ans:
        command: git commit -m "any message", to commit the file
        command: git push 
