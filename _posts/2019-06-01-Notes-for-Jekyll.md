---
layout: post
title: "Things to Remember"
date:   2019-06-01 15:47:42 -0400
categories: trial and error
---

## Some things you should try to remember:

### front matter
Front matter is located between the two pairs of three hyphens

Front matter can be written in YAML or JSON (Liquid uses YAML)

you can also set front matter defaults in the config yml file by setting up an array with defined values

### layout
layout gives the file its skeleton of code that applies formatting

the name of the page pulls directory from the file name in the posts folder, but you can override that using the front matter

### subdirectories:
if you create subdirectories in the posts folder, its not going to change how they are displayed

you can even make a drafts folder to make markdown posts in progress, and 'serve' the drafts folder 

> serve --drafts

from the terminal, but if you want them to run normally, you have to move them to posts and give them a date

### pages
you can make pages instead of posts by making a markdown file in the main folder

give it a .md and in the front matter, make it a page

pages don't log the time?{: style="color: red"}
apparently the only real difference is pages do not allow for a disqus comments section  

also, you can make permalinks for pages using the permalink and giving it a variable, for gallery I gave it '/gallery'

### themes and layouts
by default, you are using minima, you can check in the config yml file

You can find more themes by searching for Jekyll Themes at [Ruby Gems](https://rubygems.org)

Add the gem to the Gemfile, then go to the terminal and enter bundle install to download the theme

Some themes do not have defined layouts like "page" or "post"

You can create these layouts by making an html page and overriding the exising layouts, or making new ones

you can also define different levels of layouts, like wrappers to make parent-child layouts

### variables
variables allow you to access front matter variables and have them  display as part of the page

take a look at Jekyll Documentation which has a long list of all the variables that you can access

### brush up on html to try out:

you can use 

1. includes (headers, footers) things that go on ever page 

2. loop throughs 

3. conditionals

### Questions for Alex

How to get images up onto a static site, is there any way to have the images stored locally?

Github repository, hosing on Github, how does it work, what are pros and cons? How do I do this:

> Common problem #7: Again, you don’t need to build your Jekyll website locally in order to write a blog post locally and publish it to your website. You can write the Markdown post locally and push it with any images you’ve used, and then GitHub Pages will rebuild the website for you on the server.


Repository terminology--forked repositories, master

Sublime vs CMS software, is using the text editor just making a static site the "hard way?"












