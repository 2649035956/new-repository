#             Github

## 关键字查询:

	awesome,去此标签类别中查询项目
	(python) tutorial , 查询(python)相关资料、书籍、文档
	(socket) sample , 查询对应技术(socket)对应的代码

## GitHub三要素:
### Repository 仓库:
	仓库是github项目管理存储基本单位
	一个仓库中存储一个项目，一个用户可以拥有多个仓库，一般仓库分为public，private
### Commit 提交:
	程序员在整个开发周期，有大量的对代码资源的选代和修改，都可以通过commit的方式进行记录,便于程序员回溯代码，即使这些代码被删除
	提交便于使用者观察整个工程的开发流程以及设计流程
### Branch 分支:
	在仓库中可以包含多个分支，分支才是代码文件的第一存储单位，默认的仓库主分支为master/main
	*不仅可以管理代码存储，便于多人协作开发
![picture](https://picture.gptkong.com/20240610/14252c28dd7d874585afa7958816092321.png "分支")
## 仓库内容:
	Code，资源存储，代码资源，二进制，项目管理脚本，许可证等等
	issues，使用时遇到的bug或 进行提交，等待反馈
	README，使用markdown语言编写，工程自述文述，开发进度，版本更新，使用介绍等等
	LICENSE许可证:GPL2.0,3.0.Apahce 2.0，Mit，这些许可证，给使用者最大使用权限以及最少的限制
## Git软件，分布式版本控制系统:
	仓库管理软件，使用git管理私人代码或企业代码
![picture](https://picture.gptkong.com/20240610/1439fc8f77500e4428bcf614ff19d4a92d.png "软件")
## 设备认证:
### 1、让网站的账户与设备绑定，后续完成代码的管理，上传下载
	


Markdown, 文本修饰语言，用特殊符号修饰正文效果<br>


## 标题修饰符\#

# 标题修饰符(一级标题)
## (二级标题)
### (三级标题)
#### (四级标题)
##### (五级标题)

## 正文内容

	输入正文内容：但是如果需要换行，用\<br\> 标签

## 修饰正文

*测试文本*<br>

**测试文本**

***测试文本***

~~测试文本~~

这是一段测试文本，用`关键字`修饰

##分割线
  用\-\-\-表示分割线
---

##引用效用\>表示
> addddd
>> add
>>> 三级引用
>>>> 四级引用

## 列表修饰符
### 无序列表 \*
* turn
  * reverse 1999
    * regules
* open world
  * genshin
    * hutao
### 有序列表 1.

1. colin
  1. c
  2. c++
  3. online and mysql

2. school
  1. c++
  2. java
  3. struct

### 混合列表
1. 测试一
  * 测试二
    2. 测试三

### 表格(对齐方式)

名称|科目|周期
--|:--:|--:
colin1|c|32
colin2|c++|32
colin3|online and mysql|32
colin4|linux|32

### 代码片段
```c
	#include <stdio.h>
	using namespace std;
	int main(void)
	{
		printf("test code\n");
		return 0;
	}
```
```cpp
	#include <iostream>
```
```python
	import <os>
```
```bash
	echo "test"
	pwd
	ps aux
	ls -l
```
### 超链接技术

[github](https://www.github.com "点击访问")

### 插入图片

	![图片](地址 "悬停标题")
