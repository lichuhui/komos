---
title: Hello Test3
tags:
- 标签2
- 标签3
categories:
- 分类2
- 分类1
- Hello
---

here is the excerpt...来点中文
<!-- more -->

``` language-javascript
function test() {
  var a = 1;
}
```

``` language-css
.article-header a {
  color: #FFF;
}
```

``` language-scss
.article {
  margin-bottom: 1.4rem;
  padding: 0.8rem;
  -moz-box-shadow: 0.3rem 0.3rem 0.8rem $article-box-shadow;
  -webkit-box-shadow: 0.3rem 0.3rem 0.8rem $article-box-shadow;
  box-shadow: 0.3rem 0.3rem 0.8rem $article-box-shadow;
  .mask {
    overflow: hidden;
    height: 1rem;
    &:after {
      content: '';
      display: block;
      margin: -2.5rem auto 0;
      width: 100%;
      height: 2.5rem;
      border-radius: 4rem/0.1rem;
      box-shadow: 0 0 0.1rem $article-footer-border-top;
    }
  }
}
.article-header a {
  color: $article-link;
}
.article-excerpt {
  color: $article-link;
  i {
    color: $article-quote-color;
  }
}
.article-footer {
  padding-top: 0.2rem;
  a {
    text-decoration: none;
    color: $article-link;
    &:hover {
      font-weight: bold;
    }
  }
}
```

Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` language-bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` language-bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` language-bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` language-bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)
