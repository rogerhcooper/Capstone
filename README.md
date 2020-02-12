# Capstone
Install Git
https://git-scm.com/downloads

Install Python with custom installation, make sure you have pip selected
https://www.python.org/downloads/

Install pipenv
In your terminal:
pip install pipenv

Install Flask
In your terminal:
pip install flask

If you do not have a text editor you have/like, install Visual Studio Code at: https://code.visualstudio.com/
Visual Studio Code also has a built in console if you use the keyboard shortcut 'ctrl + `'

fork the repo
In the top right of your page, click on the fork button.
If you don't know what forking means read this:
https://help.github.com/en/articles/fork-a-repo

clone the repo
On the the page of your forked repo click on the green button that says "Clone or download".
Copy the link in the menu that pops up.
Open up your terminal and go to the folder you want to clone this project.

Run the command:
git clone
This link is the link you copied from the "Clone or download" button

You should also clone the main repo so you can view the main project in it's current state.

In your terminal:
Go into the project folder you just cloned
cd KentEvent

Create a remote of the repo you forked from
git remote add upstream
Pushing/Pulling Add all files before you commit
git add *

Commit your added files
git commit -m"message about changes"

Push your commits to the repo from your fork
git push upstream master

Always test the project in your own fork before pushing into the main repo. Always push from your fork and never from the main repo

#Pull the current version of the main repo into your fork
git pull upstream master

#Pull the current version of the main repo into your clone of the main repo
git pull

#Installing packages
pipenv install


#Set environments
Windows PowerShell:
$env:FLASK_APP = "flaskr"
$env:FLASK_ENV = "development"

Mac Terminal/Linux:
export FLASK_APP=flaskr
export FLASK_ENV=development

Install packages: pipenv install

Start your pipenv virtual environment

pipenv shell


#Start the project
flask run
