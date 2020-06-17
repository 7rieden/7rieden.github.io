---
layout: post
title: Build a Jekyll Blog 1
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
<br>
Download Ruby+Devkit and install on [Ruby Website](https://rubyinstaller.org/downloads/)
<br>
![Ruby site](img/Install_Ruby.png "Ruby Website")

<br>
## <b>Step 2: Installing Jekyll in Windows</b>
<br>
##### 1. Run `cmd`, `Windows Terminal`, or `Start Command Prompt with Ruby`.

##### 2. To check the version of ruby,
```bash
ruby -v
```
##### 3. Install Jekyll to path you want (like `C:\7rieden.github.io\').

##### 4. Make your blog folder
```bash
mkdir c:\7rieden.github.io
cd c:\7rieden.github.io
```
```bash
gem install jekyll bundler
```
##### 5. Create a jekyll blog on your local machine

&nbsp;&nbsp;If  you have any errors, type

```bash
chcp 65001
```

&nbsp;&nbsp;publish the blog locally

```bash
jekyll serve
```
&nbsp;&nbsp;or

```bash
bundle exec jekyll serve
```


##### 6. You can check local server [http://127.0.0.1:4000/](http://127.0.0.1:4000/) or [localhost:4000](http://localhost:4000/) with browser