# my-cache-gjs
my-cache-gjs   缓存工具，简短，精悍
hello world

## 安装http-server
npm install http-server -g or --save-dev

## 安装gitbook
npm i gitbook-cli --save-dev
gitbook init ./my-cache-gjs (在dos下使用此行命名，在mayuncode文件夹下使用)

检查是否.gitignore配置成功的方法

git status 看不见变化即可

# npm 账号注册（npm config set email myemail@gmail.com 可能出现的bug解决方法）
$ npm adduser
Username: sanjin2
Password: a13295644084
Email: (this IS public) (1437890879@qq.com)
Logged in as sanjin2 on https://registry.npmjs.org/.
相关blog
https://zhidao.baidu.com/question/1945763867802165628.html
https://blog.csdn.net/rushichunqiu/article/details/80497573

# npm 提交版本
npm add user
npm login
npm publish .

# releases
## 创建名为 v0.0.1的tag
git tag -a 'v0.0.1' -m 'first version'
## 将当前分支提交到 v0.0.1 tag
git push origin v0.0.1

# 拉分支
git checkout -b dev
git branch

# 合并分支
git checkout master
git merge dev
git push origin master

# 远程拉取代码
git pull origin master


