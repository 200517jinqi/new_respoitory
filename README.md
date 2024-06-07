## 笔记正文
Github<br>
关键词查询：awesome。去此标签类中查询项目<br>
            python tutorial，查询资料，书籍，文档<br>
            socket sample 查询对应技术的代码样本<br>
Github三要素：<br>
Respository 仓库<br>
仓库是github项目管理存储基本单位<br>
一个仓库中存储一个项目，一个用户可以拥有多个仓库，一般仓库分为public，private<br>
commit提交：<br>
程序员在整个开发周期，有大量的对代码资源的迭代和修改，都可以通过commit的方式进行记录，便于程序员回溯代码。<br>
提交便于使用者观察整个工程的开发流程以及设计流程<br>
Branch分支：<br>
分支才是代码存储单元<br>
在仓库中可以包含多个分支，分支才是代码文件的第一存储单位<br>
默认的仓库主分支叫master/main<br>
不仅可以管理代码存储，便于多人协作开发<br>
例子：<br>
做一个抖音项目：<br>
master主分支：程序主要资源与逻辑<br>
新建分支1：智能推荐（协同过滤）<br>
新建分支2：支付系统，打赏系统<br>
此时这个仓库便有了三个分支。<br>
仓库内容：<br>
code：资源存储，代码资源，二进制，项目管理脚本<br>
issue：使用时遇到的bug或异常进行提交，等待反馈<br>
code中的文件：<br>
readme：帮助文档，使用markdown语言编写，工程自述文件，开发进度，版本更新，使用介绍等等。<br>
license：许可证。权限很高的许可有：GPL2.0、GPL3.0、Apahce2.0、Mit这些学科正，给使用者最大使用权限以及最小的限制<br>
Git软件：分布式版本控制系统<br>
仓库管理软件，使用git管理私人代码或企业代码<br>
设备认证：<br>
1.如何让网站的账户与设备绑定，后续完成代码的管理，上传下载<br>
命令：git config --list    //查看git配置文件<br>
      git config --global user.email”邮箱”<br>
      git config --global user.name”用户名”<br>
      git init 创建本地仓库<br>
      ssh-keygen -t rsa -C “注册邮箱”   //创建本地密文<br>
      ssh -T git@github.com    //检测绑定是否成功<br>
      git remote add origin”仓库地址”  //给仓库取别名<br>
2.为目标仓库起别名，定位目标仓库，后续上传<br>
本地设备与云端仓库的交互逻辑：<br>
git add code.c将代码传送到git缓冲区，再用git commit”写提交说明”将代码传送到本地仓库，然后再用git push origin master上传到云端仓库，如果两者的主分支名字一致，则合并分支。本地(Master)，云端(Main)，如果不一样，则会新建立一个分支。<br>
git status 查看仓库状态<br>
git add //添加内容<br>
git rm //删除本地数据并删除仓库数据<br>
git restore //恢复被删除的数据(仓库里有数据)<br>
代码更新的依赖关系被破坏：<br>
本地内容要比云端新，完成更新替换，但是如果直接修改云端内容，会导致本地内容无法提交。<br>
解决方法，先拉取git pull云端内容与本地内容合并或操作，而后再次推即可。<br>
对应命令：git pull --rebase origin master<br>
          git rebase --skip  //忽略本地内容，保存云端内容<br>
          git rebase --continue  //忽略云端内容，保留本地内容<br>
下载开源代码：<br>
git clone “https网站地址”  //下载开源代码<br>
分支Branch：<br>
关于分支的相关命令：创建分支，选择分支，合并分支等等。<br>
Markdown语言：<br>
github可以编写readme，文本修饰语言<br>
#加空格为标题修饰符，叫做一级标题<br>
##加加空格为二级标题<br>
后面一次类推，区别是字体会越来越小<br>
分割线用\-\-\-表示<br>
表格用“|”分隔开，左对齐用“--”表示，中间对齐用“:--:”表示，右对齐用“--:”表示<br>
代码片段用“\`\`\`”表示<br>
<br><br>
<br><br>
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
## 分割线
  用\-\-\-表示分割线

---

## 引用效果用\>表示
> 你自己就是一座近况，关键在于如何挖掘和利用自己
>> 苏格拉底
>>> 三级引用
>>>> 四级引用

## 列表修饰符
### 无需列表 \*
* 二次元
  * 原神
    *八木童子
* 大逃杀
  *PUBG
  *APEX



### 有序列表 1.
1. 物理学
  1. 粒子物理
  2. 原子核物理
  3. 凝聚态物理
2. 计算机科学
  1. 分布式架构
  2. 云计算
### 混合列表
1. 测试一级
  * 测试二级
    2. 测试三级

### 表格
名称|技能|排行
--|:--:|--:|
蝙蝠侠|有钱|32
海王|游泳|16
闪电侠|跑|18

### 代码片段

```c
	#include<stdio.h>
	int main(void){
		printf(test code\n);
		return 0;
	}
```

```cpp
	#include<iostream>
```

```python
	import<os>
```

```bash
	ls
	cd
```

## 超链接技术

[Github](https://www/github.com/ "点击访问")<br>
[点击重新跳转本页](https://github.com/200517jinqi/new_respoitory?tab=readme-ov-file)<br>

### 插入图片
![测试图片](C:\Users\DELL\Desktop)

