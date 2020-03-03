# Capstone

Install Git
<br>
https://git-scm.com/downloads
<br>
<br>
Install Python with custom installation, make sure you have pip selected
<br>
https://www.python.org/downloads/
<br>
<br>

<h3>Instructions for setting up a remote repo</h3>
<br>
fork the repo
<br>
In the top right of your page, click on the fork button. 
<br>
If you don't know what forking means read this: 
<br>
https://help.github.com/en/articles/fork-a-repo
<br>
<br>
clone the repo
<br>
On the the page of your forked repo click on the green button that says "Clone or download". 
<br>
Copy the link in the menu that pops up.
<br>
Open up your terminal and go to the folder you want to clone this project.
<br>
<br>
Run the command:
<br>
git clone 
<br>
This link is the link you copied from the "Clone or download" button
<br>
<br>
You should also clone the main repo so you can view the main project in it's current state.
<br>
<br>
In your terminal: 
<br>
Go into the project folder you just cloned
<br>
cd Capstone
<br>
<br>
Create a remote of the repo you forked from
<br>
git remote add upstream 
<br>
Pushing/Pulling
Add all files before you commit
<br>
git add *
<br>
<br>
Commit your added files
<br>
git commit -m"message about changes"
<br>
<br>
Push your commits to the repo from your fork
<br>
git push upstream master
<br>
<br>
Always test the project in your own fork before pushing into the main repo. 
Always push from your fork and never from the main repo
<br>
<br>
Pull the current version of the main repo into your fork
<br>
git pull upstream master
<br>
<br>
Pull the current version of the main repo into your clone of the main repo
<br>
git pull
<br>
<br>
<h3><u>To work in VS Code</u></h3>
<br>
<br>
If you don't have VS Code:
1. Switch to a B.A. because you aren't a real CS Major
<br>
<br>
In VS code open the cloned repo (Capstone)
<br>
Download the extension Live Server
<br>
When you want to run the code, push the go live button in the bottem right
<br>
<br>
Prod Server:
<br>
3.17.201.134/index.html