# Pure

A responsive pure theme for [Hexo](http://hexo.io/).

- Based on [Landscape](https://github.com/hexojs/hexo-theme-landscape/)
- Powered by [Pure.css](http://purecss.io/layouts/blog/)
- [Preview]()

## Installation

### Install

``` bash
$ git clone https://github.com/saintwinkle/hexo-theme-pure.git themes/landscape
```

### Enable

- Modify `theme` setting in `_config.yml` to `pure`.
- Modify pagination settings:
```
archive: 1
category: 2
tag: 2
```

### Update

``` bash
cd themes/pure
git pull
```

## Configuration

``` yml
title: Pure # site title
author: Twinkle # your name
description: Creating a blog layout using Pure # description or subtitle
email: # used for gravatar

# if you copy an avatar file to ./source folder,
# just uncomment the variable below,
# and replace "avatar.png" to your image name.
# better to use 48x48px.
#avatar: avatar.png

# menu buttons in header
menu:
  archives: /archives
  about: /about

# comments system
disqus_shortname: 
duoshuo_shortname: 

# social links
weibo: # id but not nickname, example: levicorpus / 1997375853
github: # username, example: saintwinkle
gplus: # google+ id, don't forget symbol "+", example: +周一
twitter: # username, example: saintwinkle

# google analytics, example: UA-12345678-1
google_analytics: 
```