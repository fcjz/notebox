# Notebox

[![Join the chat at https://gitter.im/fcjz/notebox](https://badges.gitter.im/fcjz/notebox.svg)](https://gitter.im/fcjz/notebox?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

这是fcjz的notebox，译为便条箱，实际上，它是fcjz的数字花园。

地基是TiddlyWiki和一些脚本，种子来源于笔者的想法和思考。

以下是预览：

![notebox](https://github.com/fcjz/notebox/blob/main/notebox.png)

![note](https://github.com/fcjz/notebox/blob/main/note.png)

大概以后会拥有一个imfcjz.com的域名，那么这个花园的域名会是：imfcjz.com/notebox或者notebox.imfcjz.com。

日后可能会根据现有的自定义推出一个TiddlyWiki模板（这算是发行版吗？）供大家使用，敬请期待。

祝我好运，各位。

（PS：目前在国内访问速度较慢，笔者还没有配置cdn，最好使用不同的上网方式访问）

## 安装

本项目暂无npm包，所以无法使用npm相关命令进行安装，不过之后会有的。

最简单的安装方式是访问项目介绍右侧的release，找到最新版本，下载assets中的notebox.html文件到你的电脑本地，双击即可在浏览器中打开了。

你还可以通过nodejs或导入到TidGi将html转换成文件夹形式使用，可以更好地备份和同步。

## 使用

notebox使用TiddlyWiki制作，这个项目对于熟悉TW的用户而言比较简单，对于没有接触过TW的人来说可能使用起来会遇到困难，所以建议用户在使用前对TW有一个大致的了解再来使用该项目，不用很多，学会基本的新建/编辑条目、导入/删除插件之类就可以了。TW也是一个开源知识管理工具，你可以在GitHub上找到它和它的作者。

你可以将notebox当作一个TW发行版来使用，即便它主打的是其中的笔记——作者想要开源的其实是想法，不过好像更多的人对Wiki本身更感兴趣。

notebox预装了许多插件，基本上开箱即用，因此不用担心配置的问题，并且笔者也会随时间更新好用的、适合个人知识管理的插件。

notebox可以有3种使用方式：

### 单文件版

也就是那个最简单的安装方式，直接在浏览器中打开、使用、保存和备份，建议一同安装timimi，这是一个TW保存和备份插件，很好用。

### 移动端

可以使用tiddloid软件，支持导入文件和文件夹，单文件版可以使用网盘同步，nodejs版可以使用插件同步。

### nodejs版

可以将单文件转换成文件夹或导入到TidGi使用，TidGi是由林一二制作的TW客户端，可以自动保存、备份、同步到GitHub。

主要就是这三种使用方式，其实保存方式还有很多，但在这里就不细说了。

## 快捷功能

部分插件包含快捷功能，可以通过快捷键运用，方便简单，记录你的想法。

ctrl+p:唤出命令面板，可以搜索各类tiddler、标签，创建条目，输入“？”查看帮助。

alt+c:唤出inbox记录，直接输入你的想法，键入回车，保存。

alt+h:唤出键盘快捷键列表。

ctrl+g:唤出插件，可以进入安装。

## 使用notebox创建网站

单文件版可将HTML文件命名为index.html，使用git工具同步到网站仓库，使用GitHub pages生成静态网站。

nodejs版等待补，这个笔者目前还没有尝试过。

## 项目发展愿景

我目前还未将发展愿景定下来，我看过了GitHub的opensource.guide，觉得有必要想一想，这会对以后项目建设有好处。

目前比较关键的问题是，我究竟是要将这个知识库做成个人也就是我,fcjz的知识库，还是将其完全开放，允许任何人发表想法、添加条目并PR。

余下的问题基本上都围绕这个问题展开。

也许我应该专门添加一个“note”文件，来记录自己对于这个项目的规划。

2022/10/29更新：目前notebox进入内测阶段，已设置为密码访问，待笔者将其完善后开放，时间不会很长。

2022/11/06更新：目前notebox已解除内测，已设置为免密访问，对所有人开放，笔者已对项目有了大致的打算，建立了[note](https://github.com/fcjz/notebox/blob/main/note.md)文件，可以访问以查看项目的最新进程与未来计划。

## 数字花园配置

地基为TiddlyWiki（最新版本5.2.5），主题为whitespace。

已安装插件（截至2022/12/20，共计72个，均为最新版本）：

- Echart
- checklist
- click effect
- CodeMirror系列
- aggregation
- favorite
- fishing系列（包括渐进阅读）
- help
- hotzone
- KaTeX
- markdown
- notion page系列
- projectify
- relink
- shiraz
- template list
- todolist
- appear
- grb
- Splash Screen
- Respawn
- locator
- Command Palette
- pinyin-fuzzy-search
- Aggregation
- Diary
- Emoji Button
- encryptTiddler
- HTML Button
- ManageTOC
- Mark Button
- Page TOC
- QuickNotes
- Some shortcuts
- Tiddler Commander
- pinboard
- searchwikis
- dynannotate
- dynaview
- feather-icons
- hightlight
- pikaday
- QR Code
- RefNotes
- section editor
- tamasha
- tiddlywiki garden
- timelines
- trashbin
- utility
- tidgraph
- Railroad
- react.js
- reveal.js
- tw-whiteboard
- Talk Timer

预备添加：

- sitemap

- tiddly-giscus

封面图片（来源：pexels可商用图片）：

[gray](https://github.com/fcjz/notebox/blob/main/pexels-photo-3490393-.png)

花园主题：几乎所有东西，主要是哲学、设计、写作、编程、计算机之类，还包含日常的一些日记和各种各样的思考。

碎片想法能够连接在一起形成的文章将被收录在[fcjz的blog](https://fcjz.github.io/blog)中，笔者建议将notebox和blog配合食用，效果更好。

笔者的工作流与知识管理流程如下（这是两个月之前的图像，目前有所改变，改日会重新绘制一幅作为读者参考）：

[knowledge](https://github.com/fcjz/notebox/blob/main/%E4%B8%AA%E4%BA%BA%E5%B7%A5%E4%BD%9C%E6%B5%81.png)

如果你在notebox有了什么想要评论的内容，可以在这个仓库中提issue，笔者看到会回复的，不久笔者就会制作一个issue模板。

## 许可证

本项目使用AGPL-3.0许可证。

## 目前已知的插件冲突

主题WhiteSpace似乎与插件appear冲突，在同时安装两样时，从外部导入图片和其他文件时会出现尴尬的JavaScript内部错误。

插件feather-icons在检索图标之后（或者之前）不能点击图标，会出现JavaScript内部错误，应该按照插件readme的命令使用羽毛图标。定制尺寸出现问题时也会弹出错误框，建议只设置味m3或者干脆不设置大小？使用良好，有了图标之后漂亮多了。

目前tw-whiteboard还无法正常使用，笔者正在努力修复中。

不知道为什么，echats图表似乎无法正常工作？输入热力图代码无效，出来的是空白，但输入思维导图代码就可以出现生动的图表，我不知道这是为什么，在向相应的存储库发出issue。
