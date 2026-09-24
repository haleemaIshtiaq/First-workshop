# My First Git Workshop 
## Task 1:
### 1- Initialize local Git repository:

 - Create a project folder 
            ` mkdir First-Workshop` 
            ` cd First-workshop `

        Created a folder for my workshop and navigated into it.

- Initialize Git
           `git init`

        Initialized a new local Git repository

- Create a README file
           `echo # My First Git Workshop > README.md`

         Created README.md file and write the main heading  

- Check the status
           `git status`

         Its red showing that changes has not been staged and commited  

- Stage the README file
            `git add README.md`

        README.md file has been added to staging area.    

- Check the status
           `git status`

         Its green showing that changes has not been commited  yet.

- Make the first commit
         `git commit -m "Initial commit: Add README.md" `

        Saved the README file in the Git repository

- View commit history
         `git log --oneline`       

        Showed the first commit as I made only one commit.


2- Connect to GitHub

      - Create a new repository on GitHub
      - git remote add origin https://github.com/haleemaIshtiaq/First-workshop  is used for connecting local repository to gitHub
      - `git remote -v` used to verify remote connection
      - ` git push -u origin master ` is used to upload local commit to GitHub





