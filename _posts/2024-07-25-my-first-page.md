---
layout: post
title:  "zza's first page"
date:   2024-07-25 12:00:00 +0800
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
- Git到Github仓库
---