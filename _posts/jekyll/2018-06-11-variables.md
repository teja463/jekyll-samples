---
layout: "post"
title: "Variables"
categories: jekyll
permalink: /:categories/:title
author: Teja
---

You can create variables in different scopes. Front matter is the place where you declare or define your variable. The place you declared the variables will define how you access them. If you declare a variable in a layout template i.e. in the front matter of the .html files in the `_layouts` folder you can access them using `{{ layout.variable_name }}`. 

The 

If you have declaret a variable in the page/post front matter you will access them using `{{ page.variable_name }}`. You can also access the site variables i.e. the variables that are defined in the `_config.yml` using `{{ site.variable_name }}`.

There are many more default variables available in Jekyll. You can find more information at [https://jekyllrb.com/docs/variables/](https://jekyllrb.com/docs/variables/)