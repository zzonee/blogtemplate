---
title: "post下的另一篇文章"
date: "2018-06-23"
categories:
- "test"
tags:
- "Rust"
- "Programing"
toc: true
---

Title =  "zone的个人笔记"
LanguageCode = "zh-CN"
BaseUrl = ""
Theme =  "next"
MetaDataFormat =  "yaml"
CanonifyUrls =  true
BuildDrafts =  false
PaginatePath =  "p"
Paginate = 8
DisablePathToLower =  false
HasCJKLanguage = true
PreserveTaxonomyNames = false
UglyUrls = false
PygmentsStyle = "monokai"
pygmentsCodefences = true
pygmentsCodefencesGuessSyntax = true
DefaultContentLanguage = "zh"

[Params]
  Introduce = "Programmer"
  Description = "zone | 博客 | 软件 | 架构 | Golang"
  Keywords =  "博客,程序员,个人,思考,读书,笔记,技术,分享,Golang"
  Subtitle = "biu biu biu"
  #Imglogo = "/img/logo.png"
  AuthorImg = "/img/author.jpg"
  DateFormat = "2006-01-02 15:04:05"
  YearFormat = "2006年"
  MonthFormat = "01-02"
  #BaiduStatsId = ""
  #QQStatsId = ""
  #RevolverMapId = ""
  Fancybox = true


[Author]
  Name = "zone"

[Params.Share]
  #DuoShuo = ""
  Baidu = true

[Params.utterances]  # https://utteranc.es/
  owner = ""         # Your GitHub ID
  repo = ""          # The repo to store comments


[[Menu.Main]]
  Name = "首页"  
  Pre = "home"
  URL = "/"     # 渲染 ./content/post/ 下的文件
  Weight = 1
[[Menu.Main]]
  Name = "go"
  Pre = "book"
  URL = "/categories/go/"
  Weight = 2
[[Menu.Main]]
  Name = "k8s"
  Pre = "archive"
  URL = "/categories/k8s/"
  Weight = 3   
[[Menu.Main]]
  Name = "归档"
  Pre = "archive"
  URL = "/categories/archive/"
  Weight = 4 
[[Menu.Main]]
  Name = "关于"
  Pre = "user"
  URL = "/about"
  Weight = 5

[[Params.Socials]]
  Name = "GitHub"
  Icon = "github"
  URL = "https://github.com/zzonee"

