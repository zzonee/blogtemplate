---
title: "post下的一篇文章"
date: "2018-06-02"
categories:
- "archive"
tags:
- "Rust"
- "Programing"
toc: true
---

Title =  "zone的个人笔记"
LanguageCode = "zh-CN"
BaseUrl = "http://lanlingzi.cn/"
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
  #BaiduStatsId = "0b07433b4ab8d587dae7d34e71973839"
  #QQStatsId = "58416275"
  #RevolverMapId = "5b4f2ucxar6"
  Fancybox = true


[Author]
  Name = "zone"

[Params.Share]
  #DuoShuo = "lanlingzi"
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
  URL = "https://github.com/xtfly/"

