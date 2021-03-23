# Git and Git-hub set-up guide
## Part 1: Getting Started 

- Have Git installed on your computer
- Create a Github account

## Part 2 : SSH and ID

- Generate an SSH key to allow your local machine to push changes to your Github account
- Type 
```ssh-keygen -t ed25519 -C "your_email@example.com"``` and make sure that the email you enter is the same one associated with your Github
- Type ``` cd ~/.ssh``` followed by ``` ls ```
-Navigate to the ```id_rsa.pub file``` and open it via text editor
- Go to your user profile on Github, enter the settings, go to the "SSH and GPG keys", and add the SSH key for the text editor in the appropriate input field

## Part 3 : Setting up a Repositry
- create a folder for your project on your machine
- Initialise the repository with git init
- In this folder, create a file called README.md via the command touch README.md
- Edit the contents of the file with the text editor of your choice
- Add the files you created to the temporary repository by using git add <name of the file>, you can check the status of your repository by typing git status
- Write a commit with git commit -m "first commit"
-type git config --global user.email "<your_email@example.com>"
-finally git push -u origin main
  
 # DONE
