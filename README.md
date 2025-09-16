## Programmer Assessment Q4

- Numbered steps  
- Code blocks for commands  
- Inline emphasis for `y` and file names  
- Clickable link to your local host  

This repository contains a broken web app built with Dash. Please follow the tasks below.

Tasks:
1. Clone this repo to your machine.
2. Fix missing dependencies and fill authors section in `pyproject.toml`.
3. Fix bugs prevent the app `main.py` from running.
4. Change port the app ruuning on to `10030`.
5. Commit you changes.
6. Update `README.md` with a instruction
   1. Assuming the user has a fresh minimum Linux installation with no python.
   2. Setup python and virtual environment for this app, remember to use the fixed `pyproject.toml`.
   3. How to run this app and how to access it without portforwarding.
7. Push all the changes to your own repository on Github, and provide a link to your own repo in your submission in the last.

Starting with fresh linux with no python,
First run 
         sudo apt update
         sudo apt install python3 python3-pip python3-venv

You should be prompted to type y (yes) for this to start downloading.
mkdir new_project (or any appropriate name) and then add the needed files
Then go to your directory
CD/path/..... the path to your directory
Create a virtual environment 
         python3 -m venv venv
         source venv/bin/activate
install and upgrade pip which is pythons package handler (will read from pyproject.toml the needed dependancies)
         pip install --upgrade pip
         pip install
run the applicaiton
         python main.py
This will start running (as it is currently) on your local host to http://127.0.0.1:10030/
It is running on this address because in main.py we changed the port number to 10030 per the instructions above.


         

