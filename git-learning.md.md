What is git-hub:-
Git hub is distributive control system. Oit offers a c loud based 
.git repository hosting service. It is command line tool. Github
make it easier for individual and teams to use git for version 
control and collaboration.

let's know more about github 
https://www.youtube.com/watch?v=uR6G2v_WsRA

Installation:-

1. Open browser
2. Visit desktop .github.com .
3. Click download for window.
4. Allow installation to download and installed and then click 
on finish.

Repository:-

It is place (file) where you have your code.
create repository:-
• Click on the right upper new option to create a repository
• Type a short and memorable name for your repository
• Choose a repository visibility either private(payable) or 
public.
• Select initialized this repository with a README 
• Click create repository.

Branch:-

Branch is a version of your repository.
A repository contain multiple branches (version).

Merging:-

Merging is way to merge your new change branch to the 
original branch. We crated branches to make it work.

SSH (secure shell protocol) key:-

With ssh key you can connect to github without supplying your 
username and personal access and password.
 
generate ssh key :-

• Open git bash.
• Paste the text and $ ssh-keygen -t ed25519 -C "your_email@example.com"
press enter.
• Enter passphrase , enter passphrase again 
• SSH key genarate then you have to add your key to you 
repository.
• Open the .ssh folder and click on “pub” then open in 
notepad and copy the text.
• Open you github setting and go to SSH option and click 
and then pate the text in box and finally click on add SSH 
key .

• GIT COMMANDS:-

• git config:- this command is used to set the Auther 
name and email address respectively to be used with 
your commit.

• git init:- this command is used to initialized a blank 
repository it create a .git folder in the current working 
directory.

• git add:- this command is used to add files to the staging 
area.

• git commit:- this command is used to save changes to 
the local repository help you keep record of all. 

 git commit –a:- this command commits any files 
you have added with the git add command and 
also commits any files you have changed.

 git commit –m :- this command records or snapshot 
the file permanently in the version 
history.

• git status :- this command display the state of current 
repository and staging area.

• git merge :- this command is used to integrate different 
branches into a single branch.

• git remote :- this command is used to connect your local 
repository to the remote server.

• git push :- this command is used to develop the content 
from the local repository to the remote repository.

• git pull :- this command used to fetch new commit and 
merge them into local branch.

• Git clone :- this command is used to create a copy of the 
target repository or create a clone in new directory at new 
place.

• git branch :- this command refers to an independent line 
of development the git branch command is used to create 
list, rename and delete branch.

• git checkout :- this command is used to switch from one 
branch to another.

• git checkout –b :- this command creates a new branch 
and also switches to it.

• git log :- this command shows a list of all the commits 
made to a repository.
 
How to push a file to github:-

1. Create a new repository. 
2.Open your git bash.
3. Create your local project in your desktop
4. Initialized the git repository (use git init command)
5. Add the file to the new local repository( use git add 
command)
6. Commit the file stage in your local repository by 
writing a commit message (using git commit –m)
7. Copy your remote repositpory’s URL from github.
8.Add the URL copied, which is your remote repository 
to where your local content from your repository is 
pushed( git remote add origin)
9. Push the file in your local repository to github(git 
push –u origin master)

https://www.youtube.com/watch?v=wrb7Gge9yoE&t=80s
