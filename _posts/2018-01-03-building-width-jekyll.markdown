---
layout: post
title:  "用Jekyll搭建博客"
date:   2018-01-03 17:55:44 +0800
categories: jekyll update
---
折腾半天，终于用Jekyll在Github上搭建好了自己的博客。期间踩了不少坑，简单记录下以备回顾。



首先，安装Jekyll:

  >`gem install jekyll`

这里要如果已安装gem，则需要注意gem版本。



安装好jekyll后就可以新建项目了
  >`jekyll new myblog`

操作成功后就可以在所在路径下找到`myblog`文件夹了。
文件夹中的配置文件`_config.yml`可以按需修改。（配置说明：https://www.jekyll.com.cn/docs/configuration/）



最后，切到项目文件夹

  >`cd myblog`

运行服务

  >`jekyll serve`




好的，可以本地访问了
`http://localhost:4000`


本地调试好了，将`myblog`下的所有代码全部push到建好的仓库中就可以了。



[Jekyll docs]:[jekyll-docs]

[jekyll-docs]: https://jekyllrb.com/docs/home
