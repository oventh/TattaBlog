# 极简博客 Ttblog
使用 python3 + django2 + sqlite + avalon.js进行开发  
### 简介
* 你可以用Ttblog搭建自己的博客平台，也可以用来作为python+django的入门学习案例  
* 后台管理使用mvvm框架avalon.js进行交互，强调操作的交互性，也便于按照自己的需要修改界面风格
* 数据库采用sqlite，轻量级也便于迁移，如果需要用其它数据源可以修改django settings，添加新的数据源。  
* 发布文章时自动抓取文章中的图片作为显示在文章列表的主图，如果文章中没有图片则采用默认图片，从而美化前台显示效果。 
### 环境
* Python v3.7
* Django v2.1.2
* Sqlite v3
* Avalon.js v2
### 计划
* 将复制粘贴过来的文章中携带的外键图片抓取到本地，然后建立链接，从而确保文章转贴完整。（原始文章的出处往往不允许外链图片，导致转贴过去以后图片不显示）
* 建立插件系统，让一些附加功能可以通过插件进行自定义。  
* 支持微信、qq等第三方平台进行登陆。 
* 支持微信公众号绑定，并且将文章回复的信息通过微信模板消息进行提醒。  
