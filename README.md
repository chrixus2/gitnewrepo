# gitnewrepo         
This lesson explain how to push code from your local environment to Github, a remote repository, highlighting the distributed aspect of Git. 
## Download Gitbash 
- https://git-scm.com/downloads
## configure Gitbash 
- git config --global username.name
- git config --global username.email
## configure environment 
- mkdir myresume 
- cd myresume  
- touch index.html 
- git init 
## Clone your repository 
- git remote add origin (this should be the url from your created repo-use https)
## Push to Github 
- git status
- git add index.html
- git commit -m "Create index.html"
- git push origin master
## Convert your file to Github pages 
- Navigate to the settings tap of your repository
- from the genal section local pages
- from the deployment and build section, select your branch document and click save
-  wait for a minute or more, then refresh the page to retrieve the github pages for the file
