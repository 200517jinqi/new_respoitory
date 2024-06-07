## 笔记正文
 github命令总结:<br>
 git config --list  //查看git配置文件<br>
 git config --global user.email "邮箱" //验证邮箱<br>
 git config --global user.name "用户名" //验证用户名<br>
 git init //创建本地仓库<br>
 ssh-keygen -t rsa -C “注册邮箱”   //创建本地密文<br>
 ssh -T git@github.com    //检测绑定是否成功<br>
 git remote add origin”仓库地址”  //给仓库取别名<br>
 git add code.c将代码传送到git缓冲区<br>
 git commit”写提交说明”将代码传送到本地仓库<br>
 git push origin master上传到云端仓库<br>
 git status 查看仓库状态<br>
 git add //添加内容<br>
 git rm //删除本地数据并删除仓库数据<br>
 git restore //恢复被删除的数据(仓库里有数据)<br>
 git pull --rebase origin master //在云端拉回文件<br>
 git rebase --skip  //忽略本地内容，保存云端内容<br>
  git rebase --continue  //忽略云端内容，保留本地内容<br>
  git clone “https网站地址”  //下载开源代码<br>

