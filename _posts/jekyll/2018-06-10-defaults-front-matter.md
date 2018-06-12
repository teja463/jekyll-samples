---
layout: post
title: Default Front Matter
categories: jekyll
permalink: /:categories/:title
---

# Front matter defaults

Lets say you don't want to define the front matter individually in all the `md` files, you can do this in the `_config.yml` file.

There can be some more options for defaults you need to explore.

```yml
defaults:
  -
    scope:
      path:
      type: "posts"
    values:
      layout: "post"
```
