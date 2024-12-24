# California-House-Pricing

# Software and tools required
1. [Github account](https://github.com)
2. [HerokuAccount](https://heroku.com)
3. [VS Code IDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

# Create a new environment

'''
conda create -p venv python==3.7 -y
'''

# setting up git
'''
(C:\Users\Ekta Gupta\OneDrive\Desktop\PROJECTS\docker project on linear regression\venv) C:\Users\Ekta Gupta\OneDrive\Desktop\PROJECTS\docker project on linear regression\California-House-Pricing>git config --global user.name "Ekta Gupta"

(C:\Users\Ekta Gupta\OneDrive\Desktop\PROJECTS\docker project on linear regression\venv) C:\Users\Ekta Gupta\OneDrive\Desktop\PROJECTS\docker project on linear regression\California-House-Pricing>git config --global user.name
Ekta Gupta

(C:\Users\Ekta Gupta\OneDrive\Desktop\PROJECTS\docker project on linear regression\venv) C:\Users\Ekta Gupta\OneDrive\Desktop\PROJECTS\docker project on linear regression\California-House-Pricing>git config --global user.email "egupta963@gmail.com"

(C:\Users\Ekta Gupta\OneDrive\Desktop\PROJECTS\docker project on linear regression\venv) C:\Users\Ekta Gupta\OneDrive\Desktop\PROJECTS\docker project on linear regression\California-House-Pricing>git config --global user.email
egupta963@gmail.com
'''

# we add those files in gitignore which we do do not want to commit in the github repository

# git cli commands

 1. to add a file in github repository
 '''
 git add requirements.txt
 '''

 2. to check status of all the added files in the repository
 '''
 git status
 '''

 3. to add all the files together
 '''
 git add .
 '''

4. to create a commit with a passed commit message
'''
git commit -m "This commit includes requirement.txt and readme file"  
'''

5. after commiting, you push the changes into the main repository
'''
git push origin main
'''