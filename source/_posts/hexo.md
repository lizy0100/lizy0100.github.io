title: Hexo 命令
date: 2015-01-28 16:50:23
categories: Hexo
tags: hexo
---

###只需要几个简单命令，你就可以完成一切。
```
hexo n #写文章
hexo g #生成
hexo d #部署 # 可与hexo g合并为 hexo d -g
```
*以上是摘要>><!--more-->以下是全文*

##常用命令：
```
hexo new "postName" #新建文章
hexo new page "pageName" #新建页面
hexo generate #生成静态页面至public目录
hexo server #开启预览访问端口（默认端口4000，'ctrl + c'关闭server）
hexo deploy #将.deploy目录部署到GitHub
```

##常用复合命令：
```
hexo deploy -g
hexo server -g
```
##简写：
```
hexo n == hexo new
hexo g == hexo generate
hexo s == hexo server
hexo d == hexo deploy
```

##自定义页面

###执行new page命令
	hexo new page "about"

在hexo\source\下会生成about目录，里面有个index.md，直接编辑就可以了，然后在主题的_config.yml中将其配置显示出来。
上述步骤，也可以手工生成，在hexo\source\下手工新建about和index.md也是完全等价的。

>因为markdown对table的支持不好，我是在about中直接建立index.tml，里面书写页面内容，hexo会帮你加上头和尾。  
