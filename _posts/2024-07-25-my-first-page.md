---
layout: post
title:  "zza's first page"
date:   2024-07-25 10:00:00 +0800
categories: jekyll update
---
- 旧版参考（已归档）-[[用Github做个人博客（作废）]]

实操
---
- 安装ruby、bundle和Jekyll
	- 安装Ruby：windows系统使用rubyinstaller安装，并勾选添加到环境变量即可。
	- 之后会弹出一个类似与CMD的处理框，在其中安装"[1,3]"
	- 随后在CMD中输入ruby -v和bundler -v检查版本和安装情况
	- 安装Jekyll，输入指令gem install jekyll bundler
- 创建Jekyll项目
	- ”jekyll new myblog”
	- 安装依赖项：bundle install
		- 这里可以先修改一下gemfile，将网址改成镜像网站
		- Gemfile里有一行带wdm的，需要删除
	- 运行Jekyll服务：“bundle exec jekyll serve”
- 配置Jekyll
	- 首先配置“config.yml”
	- 创建一个assets文件夹，可以存储一些放置到其他博客页面中的图片等资源
	- 上传一篇markdown推文到post文件夹
	- 修改About.md文件
	- 选一个logo图标，制作成favicon.ico文件，放置在根目录
- Git到Github仓库
	- 创建仓库
		- 个人主页可以命名为：zen-zhao.github.io
	- git上去
```
git init
git remote add origin https://github.com/zen-zhao/zen-zhao.github.io.git
git add .
git commit -m "create my blog site"
git push -u origin master
```
（这里出现了报错，需要将master改名为main）
```
git branch -m master main
git push -u origin main
```
（这次即可push成功）
```
git add .
git commit -m "描述你的更改内容"
git push origin main
```
（在后续更改时，使用这个 add+push 的git指令组合即可）
- 修改Jekyll网站外观-计划
	- 修改主题
	- 修改导航页
	- 个人介绍
---