主题来源： 
A [Hugo theme](https://github.com/xtfly/hugo-theme-next) port from [NexT](https://github.com/iissnan/hexo-theme-next).
----

做了部分修改。
----

hugo new 的文章自带下列元信息：   
```
---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
categories:
 - "archive"
tags:
 - "xxx"
 - "xxx"
toc: true
---
```
说明：
1. categories 为文章分类， 可以在config.toml 中配置，例如 `/categories/archive/`
   带上 categories为archive的文章将能通过该路由访问
2. tags 可以给文章加上自定义的标签，可以随便弄
3. toc 不知道有啥作用


----
克隆下来 执行 hugo server即可查看效果