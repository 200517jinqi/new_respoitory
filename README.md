## 笔记正文
 github命令总结:
 git config --list  //查看git配置文件
 git config --global user.email "邮箱" //验证邮箱
 git config --global user.name "用户名" //验证用户名
 git init //创建本地仓库
 ssh-keygen -t rsa -C “注册邮箱”   //创建本地密文
 ssh -T git@github.com    //检测绑定是否成功
 git remote add origin”仓库地址”  //给仓库取别名
 git add code.c将代码传送到git缓冲区
 git commit”写提交说明”将代码传送到本地仓库
 git push origin master上传到云端仓库
 git status 查看仓库状态
 git add //添加内容
 git rm //删除本地数据并删除仓库数据
 git restore //恢复被删除的数据(仓库里有数据)
 git pull --rebase origin master //在云端拉回文件
 git rebase --skip  //忽略本地内容，保存云端内容
  git rebase --continue  //忽略云端内容，保留本地内容
  git clone “https网站地址”  //下载开源代码
