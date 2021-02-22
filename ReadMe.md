# Github

## GitHub
A website to host your repositories online

## Git commands
Clone -> Bring a repository that is hosted somewhere like GitHub into a folder on your local machine
add -> Track your files and changes in Git
commit -> Save your files in Git
push -> Upload Git commits to a remote repo, like Github
pull -> Download changes from remote repo to your local machine, the opposite of push

-Git bash
-need NodeJS

View page repositories

>Repository folder jeffreycanuto/newsgrid
>Setting
>GitHub Pages
>Source
 >Branch:master /docs
 >then save
 >get link

folder 
npm init -y
npm i gh-pages		install github pages

package.json

  "scripts": {
    "deploy": "gh-pages -d dist"	dist folder name
  }

  "license": "ISC",
  "homepage": "https://jeffreycanuto.github.io/mywebsite"


## [1] FIRST STEP 
git init
git add .
git commit -m "first commit"
npm run deploy			~~~~~if .html is inside a folder
## [2] CREATE REPOSITORY IN GH

## [3] 
git branch -M main	//NOTE// Source: main /root
git remote add origin https://github.com/jeffreycanuto/mywebsite.git
git push -u origin main			

…or push an existing repository from the command line
git remote add origin https://github.com/jeffreycanuto/mywebsite.git
git branch -M main
git push -u origin main
