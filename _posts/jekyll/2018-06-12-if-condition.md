---
layout: "mypost"
title: "If condition"
categories: "jekyll"
permalink: /:categories/:title
---

Below is the syntax for if condition

```
    {% if page.title == "Sample" or page.title == "If condition" %}
        This will be printed for If condition page
    {% elsif page.title == "For loop" %}
        This will be printed for For loop page
    {% else %}
        This will be printed for all other pages
    {% endif %}
```