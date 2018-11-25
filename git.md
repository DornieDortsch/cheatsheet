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