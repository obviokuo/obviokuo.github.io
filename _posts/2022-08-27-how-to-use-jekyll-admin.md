---
title: How to use Jekyll-Admin plugin?
author: obvio
date: 2022-08-27 17:51:00 +0800
categories: [Blogging, Issues]
tags: [writing,bug]
render_with_liquid: false
---

很不幸，Jekyll-admin插件安装好后遇到问题导致/admin无法访问。经Google找到[帖子](http://https://stackoverflow.com/questions/71279897/jekyll-admin-fails-with-nomethoderror-undefined-method-config-files)，发现需要在_config_yml中添加一行代码：`ignore_theme_config: true`。最后后问题得到解决，真棒！👍
