---
title: How to use Jekyll-Admin plugin?
---

很不幸，Jekyll-admin插件安装好后遇到问题导致/admin无法访问。经Google找到[帖子](http://https://stackoverflow.com/questions/71279897/jekyll-admin-fails-with-nomethoderror-undefined-method-config-files)，发现需要在_config_yml中添加一行代码：`ignore_theme_config: true`。最后后问题得到解决，真棒！👍
