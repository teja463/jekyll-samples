---
layout: post
title: Creating a project in jekyll
categories: jekyll
permalink: /jekyll/creating-project
---

# Creating a new Project

If you are using windows install ruby and run the command `ridk install`. Make sure you are not behind proxy. 

Run all the options 1,2,3 one after the other, then run `gem install jekyll bundle`. This will install jekyll and builder. Once the installation is sucessfull run the below command to create a new project

**Command to create a new project**

```sh
jekyll new project-name
```

>Wait for a while it will take sometime to create a project.

Once the project is created go inside the folder and use the serve command to start the server

**Command to start server**

```sh
bundle exec jekyll serve
```