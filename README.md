# Pure

A responsive pure theme for [Hexo](http://hexo.io/).

- Based on [Landscape](https://github.com/hexojs/hexo-theme-landscape/)
- Powered by [Pure.css](http://purecss.io/)
- [Preview](http://purecss.io/layouts/blog/)

## Installation

### Install

``` bash
git clone https://github.com/saintwinkle/hexo-theme-pure.git themes/pure
```

I use `jade` instead of `ejs`, so don't forget to:
```
npm install hexo-renderer-jade --save
```

### Enable

- Modify `theme` setting in `_config.yml` to `pure`.
- Modify `pagination` settings for `archive`, `category` and `tag` in `_config.yml`.

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
# better to use 48x48 pixels.
#avatar: avatar.png

# menu buttons in header
menu:
  archives: /archives
  about: /about

# comments system
# disqus always goes first once configured
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