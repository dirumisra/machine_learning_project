# Start machine_learning_project
1.Github Accoun
2.Heroku Account
3.VS Code IDE
4.GIT CLI
5.GIT Documentation ""https://git-scm.com/docs/gittutorial"


'''''
Creating Conda environemnt

conda create -p venv python==3.7 -y
''''
Activate Conda Environment
conda activate venv/

''''
To Bull Install Use This Command
pip install -r requirements.txt

'''
To add Fille in github

git add .
or 
git add file name

....

To create virsion/commit all changes by git

git commit -m "any message"

...

To sent version/changes to github

git push origin main

'''''
To Checking all virsion maintain by git

git log

'''
To check status 

git status

'''
Note : To ignore file or folder from git we can write same naem of file/folder in .gitignore file

'''

To check remote url
git remote -v

'''

To Setup CI/CD pipeline in heroku we need 3 information

1.Heroku_Email    =   dhirajk266@gmail.com
1.Heroku_API_Key  =   379db6cd-313d-4e80-98f4-1745a63ceca7
3.Heroku_API_Name =   regression-apps-ml

''''

BUILD DOCKER IMAGE

docker build -t <image_name>:<tagname> .

'''
Note: Image Name for docker must be Lower Case

To list docker image

'''
Docker image
'''
docker run -p 5000:5000 -e POER=5000 <imageid>

'''

Stop Image
docker ps

'''
To Stop Container
docker stop <container_id>

'''
