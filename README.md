# Machine-Learning-Project


## Software and account Required

1.[Github Account](https://github.com)
2.[Heroku Account]()
3.[VS Code IDE](https://code.visualstudio.com/download)
4.[GIT cli](https://git-scm.com/downloads)42A5-E86E

Creating conda environment
```
conda create -p venv python==3.11.1 -y
```

```
conda activate venv/
```
OR
```
conda activate venv
```

```
pip install -r requirements.txt
```

To Add files to git
```
git add .
```

OR
```
git add filename or foldername
```

>Note:To ignore file or folder from git we can write name of file/folder in .gitignore.file

To check the git status
```
git log
```

To create version/commit all changes by git
```
git commit -m "message" 
```

To send version/changes to github
```
git push origin main
```

To check remote url
```
git remote -v
```

To setup CI/CD pipeline in heroku we need 3 information 

1. HEROKU_EMAIL = avisheeljambhulkar@gmail.com
2. HEROKU_API_KEY = e1b2f97e-4d07-4e93-bc8e-4ee8a49a1329
3. HEROKU_APP_NAME = ml-application


BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname> .
```
>Note: Image name for docker must be lowercase


To list docker immage
```
docker images 
```

Run docker image
```
docker run -p 5000:5000 -e PORT=5000 
```

To check running vontainer in docker 
```
docker ps
```

To stop docker container
```
docker stop <container_id>
```