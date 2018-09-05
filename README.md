# myApp

git remote add origin git@github.com:xiao000kiss-007/myApp.git(我这里用的是ssh的上传格式，email为自己的注册邮箱格式，在使用的时候记得修改自己的内容)
git push -u origin master (将本地文件上传到gitHub中)
假设你配置好了一个远程仓库，并且你想要提取更新的数据，你可以首先执行 git fetch [alias] 告诉 Git 去获取它有你没有的数据，然后你可以执行git merge [alias]/[branch] 以将服务器上的任何更新（假设有人这时候推送到服务器了）合并到你的当前分支。
