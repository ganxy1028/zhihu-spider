# 简介

## 这是什么

这是一个简易的爬虫工具，使用Python语言编写，用于爬取知乎问题中的所有图片。

## 如何使用
### 编程使用
请确保你的Python版本是3.x。main.py代码为本工具的基础，有一定编程基础的用户可自行修改使用。 

### 非编程使用

直接运行 released.exe 即可
1. 输入title，给命名用存放文件夹命名。
2. 输入question_id，知乎问题网址 ```https://www.zhihu.com/question/********/answer/########```中的`********`
3. 等待程序完成。程序第一部分为获取问题下所有图片的地址，第二部分才开始下载。

## 声明
### Master Branch
>我是偶然间在zhihu看到这段脚本，但是代码没有排版和缩进，由于好奇，将代码整理，并做了一些改动和优化。  
原始代码地址为：[https://www.zhihu.com/question/297715922/answer/676693318](https://www.zhihu.com/question/297715922/answer/676693318)  
虽然做了比较大的改动，代码的著作权仍然归原作者所有，如果作者不希望公开，请邮件联系我删除。  
我们一起来让它变得更好吧。


### This Fork
偶然在zhihu`@lw900925`的回答里看到这份代码，本python入门小白感觉很有意思，便拿来尝试了一下。在向原答主反馈某个小bug之后，闲来无事，便自己试着对代码做了些易用性修改。

`main.py` 程序即原答案下的代码，为本分支的基础，本分支下做了些修改之后发布了 `main_for_release.py` 代码，并将其打包为了可直接运行的 `released.exe`。方便使用。

和原版代码的差别有：
+ size（已修正）
+ 外部输入 title 和 question_id，更通用
+ 图片结果的保存路径为 .py / .exe 同路径；
+ 图片名称加入了answer_id，使图片按源答案分类排序。

## 写给新手

如果你是程序员，但是没有接触过Python语言，你可以稍微了解一下Python这门语言，这应该用不了多长时间，下面的教程希望可以帮到你：

[https://www.runoob.com/python/python-tutorial.html](https://www.runoob.com/python/python-tutorial.html)

如果你没有过编程经验，可以按照这篇文章（抱歉我还没写，抽时间尽快补上）中的步骤来。

## RELEASE NOTE
### v1.2
+ 代码风格的统一化
+ 一些小 bug 的修正

  
### v1.1
+ 添加功能，将抓取结果的保存路径改为 .py / .exe 的同路径；
+ 图片名称加入了answer_id，使图片按源答案分类排序。

### v1.0
+ 修正 size 变量错误
+ 将 title 和 question_id 改为外部输入
## LINKS

原zhihu回答：[https://www.zhihu.com/question/297715922/answer/677731643](https://www.zhihu.com/question/297715922/answer/677731643)


