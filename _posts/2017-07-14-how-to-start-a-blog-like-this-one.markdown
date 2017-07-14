---
layout: post
title:  How to start a blog similar to this one
date:   2017-07-14 00:37:58 -0700
categories: jekyll update
---

Steps:

* Go to [GitHub] and create a [new repository].
* Open a terminal and clone the repository.
```
git clone git@github.com:aputla/aputla.github.io.git
```
* Install Jekyll and bootstrap the repository.
```
cd aputla.github.io
gem install jekyll bundler
jekyll new .
```
* Start the server on your localhost
```
bundle exec jekyll serve
```
* Once the pages look good, push the changes to [GitHub].
```
git add --all
git commit -m "Initial Comit"
git push
```

[GitHub]: https://github.com
[new repository]: https://github.com/new
