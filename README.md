# Info
Jenkins
#########################################################
Source Code Management:
give repo url and user id(sandeep.bhutkar@gmail.com) and password @

Build:
Custom Python Builder(for this to appear install plugin "Shining Panda"
C:\Users\sbhutkar\AppData\Local\Programs\Python\Python310\python.exe

Commands
python -m venv env
call ./env/Scripts/activate.bat
pip install -r requirement.txt
pytest -v -s -m smoke --html=./Reports/report.html testCases/test_CreateCustomer.py 
################################################################################
python -m venv env
call ./env/Scripts/activate.bat
pip install -r requirement.txt
pytest ./testCases/test_Employer.py
##############################################################################
Build
Custom Python Builder
C:\Users\sbhutkar\AppData\Local\Programs\Python\Python310\python.exe
####################################################################

GIT
To push into Github - git bash commands
git init
git remote add origin (https://path of github repo)
git config --global user.name "sandeepbhutkar"
git config --global user.email "sandeep.bhutkar@gmail.com"
git add -A   this will add all fle to staging
git commit -m "some message"
git push -u origin master

Jenkins:
http://localhost:8080/
sandeepbhutkar
!
