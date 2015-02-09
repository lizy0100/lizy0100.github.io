title: "MarkdownEditing:Sublime Text 3 的 Markdown 利器"
date: 2015-01-28 17:47:53
categories: 工具
tags: Sublime
---
##MarkdownEditing
Markdown plugin for Sublime Text. Provides a decent Markdown color scheme (light and dark) with more robust syntax highlighting and useful Markdown editing features for Sublime Text. 3 flavors are supported: Standard Markdown, GitHub flavored Markdown, MultiMarkdown.
[MarkdownEditing](https://github.com/SublimeText-Markdown/MarkdownEditing#installation)

*以上是摘要>><!--more-->以下是全文*
##Installation

Note: Sublime text has a native tiny package for Markdown. However, when MarkdownEditing is enabled, native package causes some conflicts. For this reason, MarkdownEditing will automatically disable it. Since it doesn't bring anything new over MarkdownEditing, this is not a loss. But remember, when you disable MarkdownEditing, you have to reenable the native one manually (if you want).

If you are using Sublime Text 2, you have to disable the native package manually. To do that, add Markdown to your ignored_packages list in ST user settings:

``"ignored_packages": [..., "Markdown"],``

##Package Control

The preferred method of installation is via [Sublime Package Control](http://wbond.net/sublime_packages/package_control).

[Install Sublime Package Control](http://wbond.net/sublime_packages/package_control/installation)
From inside Sublime Text, open Package Control's Command Pallet: CTRL SHIFT P (Windows, Linux) or CMD SHIFT P on Mac.
Type install package and hit Return. A list of available packages will be displayed.
Type MarkdownEditing and hit Return. The package will be downloaded to the appropriate directory.
Restart Sublime Text to complete installation. Open a Markdown file and this custom theme. The features listed above should now be available.

![sample](https://camo.githubusercontent.com/35a66d68a55666133ba7911fb0ea61277740680f/68747470733a2f2f7261772e6769746875622e636f6d2f5375626c696d65546578742d4d61726b646f776e2f4d61726b646f776e45646974696e672f6d61737465722f73637265656e73686f74732f6c696768742e706e67)


## Q&a
>Q:Sublime Text(3)通过Package control安装MarkdownEditing,删除之后每次启动都报错,怎么清除相关的错误？
>A：Preference -> Package Settings -> Package Controll -> Settings User
打开后删除 markdownediting 一行即可  
Sublime Text(3)通过Package control安装MarkdownEditing后，提示此错误：
我是通过以下办法解决的，
Ctrl+Shift+p
set syntax markdown
选择：
set syntax：MultiMarkdown
解决！