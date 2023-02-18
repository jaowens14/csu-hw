# csu-hw
repo with examples and homeworks

Common things I use

projects should always be structured like this:

documents/projects/project_name/project_name/project_files and .venv

A new virtual enviroment is created in the current directory like this:

python -m venv .venv

in windows activated like this .\.venv\Scripts\activate

deactived with deactivate 

To switch git users you need to do three things:

1. set a new user name: git config --global user.name "Jacob Owens"
2. set a new email: git config --global user.email "jaowens14@protonmail.com"
3. delete the credentials in the windows credential manager located in the control panel

Typical git steps for saving and interating: 

to add all files: git add .
to commit those changes: git commit -m "the commit"
to push the changes: git push -u origin branch_name

to switch between branches: git switch branch_name

to create a package requirements list: pip freeze > requirements.txt