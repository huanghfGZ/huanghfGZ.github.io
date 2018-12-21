---
layout: post
title:  经常关注的网站
date:   2018-05-27 01:08:00 +0800
categories: 网址
tag: 关注网站
---

* content
{:toc}


系统						{#System}
====================================
+ aaa[阿里云](https://www.aliyun.com/)公有云
+ bbb[51cto](https://www.51cto.com/)技术论坛
+ 感谢[Less官网](http://lesscss.cn/)于Less官网的样式直接拷贝过来的。只是重构了JS，并且加入了Jekyll语法而已。
+ 感谢[Github](https://github.com/)提供的代码维护和发布平台
+ 感谢[Jekyll](https://jekyllrb.com/)团队做出如此优秀的产品


WEB							{#WEB}
====================================

Nginx							{#Nginx}
------------------------------------


Nginx官网[Nginx](http://nginx.org/)主页

[Nginx官网](http://nginx.org/)

[nginx github](https://github.com/nginx/nginx)

[Nginx中文文档](http://www.nginx.cn/doc/)

taobao[Nginx文档](http://tengine.taobao.org/nginx_docs/cn/docs/)

taobao[Nginx开发从入门到精通](http://tengine.taobao.org/book/index.html)

taobao[nginx平台初探](http://tengine.taobao.org/book/chapter_02.html)

[nginx教程1](https://www.yiibai.com/nginx/beginners_guide.html)

[nginx教程2](http://openresty.org/download/agentzh-nginx-tutorials-zhcn.html)

[nginx教程3](https://www.jb51.net/list/list_226_1.htm)主页



```bash
git clone https://github.com/luoyan35714/LessOrMore.git
```

Apache							{#Apache}
------------------------------------

`Apache`项目需要配置的只有一个文件`httpd.conf`，打开之后按照如下进行配置。

> 特别注意`baseurl`的配置。如果是`***.github.io`项目，不修改为空''的话，会导致JS,CSS等静态资源无法找到的错误

```bash
name: 博客名称
email: 邮箱地址
author: 作者名
url: 个人网站
### baseurl修改为项目名，如果项目是'***.github.io'，则设置为空''
baseurl: "/LessOrMore"
resume_site: 个人简历网站
github: github地址
github_username: github用户名称
FB:
  comments :
    provider : duoshuo
    duoshuo:
        short_name : 多说账户
    disqus :
        short_name : Disqus账户
```

如何写文章							{#How-to-write-document}
------------------------------------

在`LessOrMore/_posts`目录下新建一个文件，可以创建文件夹并在文件夹中添加文件，方便维护。在新建文件中粘贴如下信息，并修改以下的`titile`,`date`,`categories`,`tag`的相关信息，添加`* content {:toc}`为目录相关信息，在进行正文书写前需要在目录和正文之间输入至少2行空行。然后按照正常的Markdown语法书写正文。

```bash
---
layout: post
#标题配置
title:  标题
#时间配置
date:   2016-08-27 01:08:00 +0800
#大类配置
categories: document
#小类配置
tag: 教程
---

* content
{:toc}


我是正文。我是正文。我是正文。我是正文。我是正文。我是正文。
```

执行							{#execute}
------------------------------------

```bash
systemctl start httpd
```

效果							{#result}
------------------------------------
打开浏览器并输入URL`http://localhost:4000/`,回车。


数据库					{#databases}
====================================

MySQL							{#mysql}
------------------------------------
打开浏览器并输入URL`http://localhost:4000/`,回车。



其他						{#other}
====================================

其他开源软件
ApacheCN 中文开源组织[ApacheCN](http://www.apachecn.org/)主页

Linux公社资源站[Linux公社资源站](https://linux.linuxidc.com/)主页
用户名与密码都是www.linuxidc.com

张宴的博客[张宴的博客](http://www.apmserv.com/)主页

web文档[web文档](https://developer.mozilla.org/zh-CN/)主页



