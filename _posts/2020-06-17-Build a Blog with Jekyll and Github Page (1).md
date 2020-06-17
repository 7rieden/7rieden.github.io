---
layout: post
title: Build a Blog with Jekyll and Github Pages 1
date: 2020-06-17
permalink: /Blog
tags: [Blog]
comments: true
---
<br>
## <b>Why do i choose Jekyll?</b>
* Free
* Markdown
* Many Themes
* Easy and Fast, if you are good at building pages

Option : [Medium](https://medium.com/)  /  [Velog](https://velog.io/)  /   [Naver](https://naver.com/)  /   [Tistory](https://tistory.com)

<br>
## <b>Step 1: Installing Ruby in Windows</b>


Download Ruby+Devkit and install on [Ruby Download](https://rubyinstaller.org/downloads/)

![Ruby site](/img/Install_Ruby.png "Ruby Website")

<br>
## <b>Step 2: Installing Jekyll in Windows</b>


<b>1. Run `cmd`, `Windows Terminal`, or `Start Command Prompt with Ruby`.</b>

<b>2. To check the version of ruby,</b>
```bash
ruby -v
```
<b>3. Install Jekyll to path you want (like `C:\7rieden.github.io\').</b>

<b>4. Make your blog folder</b>
```bash
mkdir c:\7rieden.github.io
cd c:\7rieden.github.io
```
```bash
gem install jekyll bundler
```
<b>5. Create a jekyll blog on your local machine</b>

If  you have any errors, type

```bash
chcp 65001
```

publish the blog locally

```bash
jekyll serve
```
or

```bash
bundle exec jekyll serve
```


<b>6. You can check local server [http://127.0.0.1:4000/](http://127.0.0.1:4000/) or [localhost:4000](http://localhost:4000/) with browser</b>