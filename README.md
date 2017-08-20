# hexo-theme-agnes

[![Travis](https://img.shields.io/travis/giuem/hexo-theme-agnes.svg?style=flat-square)](https://travis-ci.org/giuem/hexo-theme-agnes)

> A minimal hexo theme

![](https://user-images.githubusercontent.com/8272989/29495911-e09a5372-85fa-11e7-9c38-38756953e142.png)

[Preview](https://giuem.github.io/hexo-theme-agnes/)

## Installation

1. Get theme from GitHub.

```
git clone https://github.com/giuem/hexo-theme-agnes.git themes/agnes
```

2. Modify `_config.yml` file.

``` diff
- themes: old_theme
+ themes: agnes
```

## Configuration

Edit `$themeRoot/_config.yml`. Here is an example.

``` yml
head:
  title_separate: "|"
  favicon: favicon.ico
  rss: atom.xml

header:
  nav:
    Link: "/hexo-theme-agnes/link"
    Archive: "/hexo-theme-agnes/archives"
    About: "/hexo-theme-agnes/about"
    # more ...

footer:
  since: 2015

comment:
  disqus:
```

### Link Page

1. Create a md file in `source` (e.g. source/link/index.md), edit the file.

``` markdown
---
title: Links
layout: link
---

Write someting here.
```

2. Create a data file in `source/_data/link.yml`. Format looks like this.

``` yml
Group 1:
  GitHub:
    link: https://github.com/
  Google:
    link: https://www.google.com/
Group 2:
  Hexo:
    link: https://hexo.io/
```

Full usage is at [example](https://github.com/giuem/hexo-theme-agnes/tree/example).
