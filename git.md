https://orrsella.com/2013/08/10/git-using-different-user-emails-for-different-repositories/ config email per repository git config --global user.useconfigonly true

https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control

http://rogerdudler.github.io/git-guide/index.de.html

http://guides.beanstalkapp.com/version-control/git-on-windows.html

git init

git config user.email git@kopputer.de

git add .

git status

git commit -m "initial commit"

git remote add origin ssh://kopputer:/kunden/kopputer.de/git/es6-boilerplate.git

git push --set-upstream master

git push origin

git log

git reset


Github
------------------

# clone
git clone github:requirejs/example-jquery-cdn.git

# add existing
git init
git add .
git commit -m "First commit"
git remote add origin github:/DornieDortsch/serviceworker-test.git
git remote -v
git push -u origin master

https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/

# add local user
git config user.name DornieDortsch && git config user.email

# gittest

## Setup

### Config
```
$ git config --list

$ git config --list --show-origin

$ git config --global --unset-all user.name
```

### User and Email

Configure per repository, so you can use different accounts
```
$ git config user.name "Mona Lisa"

$ git config user.name

$ git config user.email "email@example.com"

$ git config user.email
```

Configure global, if you only use one account
```
$ git config --global user.name "Mona Lisa"

$ git config --global user.name

$ git config --global user.email "email@example.com"

$ git config --global user.email
```

## Workflow
1. `$ git clone https://github.com/DornieDortsch/gittest.git`
2. `$ git status`
3. `$ git add .`
4. `$ git commit -m "Update README"`
5. `$ git push origin master`
