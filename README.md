/********************
*how to commit code to github
********************/
mkdir test
cd test
git init
touch README
git add README
git commit -m 'first commit'
git pull https://github.com/liujiangang/BinderServer.git
git remote add origin https://github.com/liujiangang/BinderServer.git
git push -u origin master

git clone https://github.com/liujiangang/BinderServer.git
会把远程的仓库及代码下载到本地。会在本地建立一个和远程仓储同名的名录。

git commit -m "edit_log" 修改文件路径
需要进入到和远程仓储同名的名录中。
把修改提交到本地的仓库中，注意不加修改路径提交不成功，更svn有点不一样。

git push 
需要进入到和远程仓储同名的名录中。
把修改提交到远程仓储中。

