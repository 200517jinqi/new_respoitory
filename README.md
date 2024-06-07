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

[Github](https://www/github.com"点击访问")

