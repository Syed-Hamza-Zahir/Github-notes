# Github Notes
This documentation will go through how to set up Git and Github.

#### Step 1: Download Git 
The first step is to download Git and Git.bash on your localhost.

[Click here to download Git]( https://git-scm.com/downloads)

#### Step 2: Generate ssh key 
You must generate a ssh key to use for authentication. 

1. Open the terminal 
   
2. Create a .ssh directory `mkdir .ssh` then open the directory `cd .ssh`

3. Now, paste the text below, ensuring to use the email associated with you Github account.

   `$ ssh-keygen -t ed25519 -C "your_email@example.com"`
 

   The Following prompts will appear. For each of these prompts  press enter
   This should generate a public and private key pair 
> Enter a file in which to save the key (/Users/you/.ssh/id_ed25519): [Press enter]

> Enter passphrase (empty for no passphrase): [Type a passphrase]

> Enter same passphrase again: [Type passphrase again]

4. Copy the `.pub` then open Github

5. When on Github, open `Settings` then `SSH and GPG keys` then click `New SSH key` . Now paste 

#### Step 3: Initializing a repo

- `git pull`

- `git init` To check what's added to be sent to git hub

- `git status` To ensure only required files are added to be sent

- `git add .` To add git all files or `git add 'name_of_the_file'`

- `git commit -m "message"` To save changes 

- `git branch -M main` **If you have not set remote branch to main**

- `git remote add origin [key]` To Add remote to connect localhost with Github repo

- `git push -u origin main` To push changes to Github 

**Clone a specific remote branch**
- `git clone --branch main git@ssh.dev.azure.com:v3/bkharrison/Azure/Azure` : git clone --branch (branch name) (git repo link)

# Git Bash Shell Commands

cd - To change directory

cd .. - To go back a directory

pwd - To print working directory

ls - To list files in a directory

nano (name)(type of file)

mkdir (name) - Create new directory

rmdir (name) - Delete directory

cat (file name) - read file

code (file name) - open file in VS code

touch (file name) - To create a file without opening it 

(program) --version - To check the version of the programe

git help - To list commands you can use 

git init - To create a new repo

git branch -m master main - To branch name from 'master' to 'main' [good practice]

git status - To view the repo, shows changes

git add - To add changed file

git commit -m "Setup a new repo and added a readme file" - -m to add a comment

git config --global user.email "[myemail]" - To add git account locally

git log - To see all the commits

git push -u eng114_devops main

git remote add origin https://github.com/Syed-Hamza-Zahir/eng114_devops.git - To connect to git online

git pull origin main --allow-unrelated-histories - To pull files from online

rm test.docx -  To remove local file 

git reset --hard - To restore that file

git log - And grab the commit number

git reset --hard commit number 

or git pull commit number

https://www.atlassian.com/git/tutorials/syncing

https://desktop.github.com/

git checkout -b dev - To switch to new branch dev

git diff - To see changes 

nano .gitignore - List files you want to ignore inc. the nano file

git clone https://github.com/Syed-Hamza-Zahir/eng114_devops.git - To clone the url repo to current folder 

git add . - For all

cp (file) (output file)- to copy files



