---
layout: "post"
title: "Accessing static files"
categories: jekyll
permalink: /:categories/:title
---

# Intro

We can say any files without any yaml front matter as static files. For example js, css, images, pdf etc. You can keep those files any where in the project. But it is better to keep them in a folder callsed `assets` in this folder you can create subfolders like img and keep images in that folder.

You can access the static files using `site.static_files`. You can loop through using for loop and find out the below variables. For jekyll it does not matter in which folder the file is placed jekyll will identify it and pick up the file.

* file.path
* file.name
* file.basename
* file.extname

## Adding front matter to static files

You can also add front matter to static files. You can do this in the `_config.yml` file using defaults front matter. You can assign some properties to some folders and check them in if conditions.

{% for file in site.static_files %}
    {% if file.extname == ".svg" %}
<img src="{{file.path}}" alt="{{file.name}}" style="width:100%"/>
    {% endif %}
{% endfor %}