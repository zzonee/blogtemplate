主题修改自： 
A [Hugo theme](https://github.com/xtfly/hugo-theme-next) port from [NexT](https://github.com/iissnan/hexo-theme-next).
----


hugo new 的文章自带下列元信息：   
```
---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
categories:
 - ""
tags:
 - "xx"
 - "xxx"
toc: true
---
```

说明：

0. 文章全部写在 `content/post/` 目录下，可以在此目录下新建自己喜欢的目录来组织自己的文章
   比如关于go语言的文章全部写在golang目录下
1. `categories` 为文章分类，比如 `k8s`, 如果之前不存在分类为 `k8s` 的文章，则会新增此分类。
   最好按/post 下的目录给文章分类，如 golang目录下的文章 全部指定`categories`为`go`
2. `tags` 可以给文章加上自定义的标签，可以随便弄
3. `toc` 不知道有啥作用


----
使用：

1. git clone https://github.com/zzonee/blogtemplate.git blog
2. cd blog && hugo server