# Zhou

> 一个风格简洁的Hexo主题

[在线预览 Preview](http://www.javion.me/)


## 下载 

``` bash
$ git clone https://github.com/javion25/hexo-theme-zhou/
```

## 使用 

将 `_config.yml` 中的 `theme` 修改为 `zhou`.

## 配置 

``` yml
# Header
menu:
  Home: /
  Blog: /archives
  Project: /project
  About: /about
logo_url: /img/logo.png
rss: /atom.xml

# Content
excerpt_link: Read More
fancybox: true

# Sidebar
sidebar: right
widgets:
- category
- tag
- tagcloud
- archive
- recent_posts

# display widgets at the bottom of index pages (pagination == 2)
index_widgets:
# - category
# - tagcloud
# - archive

# widget behavior
archive_type: 'monthly'
show_count: true

# Miscellaneous
google_analytics:
favicon: /favicon.png
twitter:
google_plus:
fb_admins:
fb_app_id:
```

## Requirements

- [Grunt] 0.4+
- Hexo 2.4+

