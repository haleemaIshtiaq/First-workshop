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
      - `git push -u origin master ` is used to upload local commit to GitHub

3-Track changes:

      - Create index file by using echo This is my First Git workshop> index.html
      - git add index.html (To move to staging area)
      - git commit -m "Add index file" (Made another commit)
      - git push (Push the commit to GitHub)
    Another file in notepad is created , added ,commited and push to GitHub in same manner.  

Modify the existing notes file: `echo I am learning Git and GitHub>> notes.txt`
Check the changes `git status` `git diff`
Stage and commit the modified file.`git add notes.txt`  `git commit -m "Update workshop notes"`

`git push` use to send commit changes to GitHub.

4- Ignoring Files:
    
- Create a secret file : `echo This is a secret file.> secret.txt`
- Create .gitignore file: `echo secret.txt> .gitignore`
- Stage and commit .gitignore file: ` git add .gitignore ` `git commit -m "Add gitignore to exclude sensitive files"`



## Task 2:Clone, Rename, Republish
  - Clone the teacher repository `git clone https://github.com/Lexicon-Smaland/Hello-World.git`
  - Enter the cloned folder `cd Hello-World`
  - Check the remote connection `git remote -v`..(Connected to teacher repository)
  - Create my own Hello-World repository on Github.
  - Connect to my repository ` git remote set-url origin https://github.com/haleemaIshtiaq/Hello-World `
  - Again check remote connection `git remote -v`..(Connected to my repository)
  - Check the current branch `git branch --show-current` (its main)
  - Modify and save README.md. Stage and commit changes.`git add README.md``git commit -m "Update README for Git workshop"`
  - Check commit history `git log --oneline`
  - Push to my GitHub repository `git push -u origin main`

  **Result:** Successfully cloned , modified and published