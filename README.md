# 自用小程序

## Features

* 新闻阅读
  - 英语新闻阅读

* 共享图书馆
  - 图书分类管理
  - 图书管理
  - 成员管理
  - 借阅管理
  - 好友间互借


....


扫码访问小程序:



## Usage

### Start

``` bash
git clone git@github.com:JusticeShi/simpleJustice.git
cd simpleJustice
npm install wepy-cli -g
npm install
npm run dev
```

> **Remind**

- 使用微信开发者工具新建项目，本地开发**选择 `dist` 目录**
- 微信开发者工具 -> 项目
  - **关闭** ES6 转 ES5
  - **关闭** 代码压缩上传
  - **关闭** 上传代码时样式文件自动补全
  - **开启** 开发环境不校验请求域名、TLS版本以及HTTPS证书


### Build
```
npm run build
```


## What's Included

- `npm run dev`
  - Compile `.wpy` files to `.wxml` / `.js` / `.wxss` etc
  - Related NPM packages
  - Copy static files
  - Watch changes

- `npm run build`: Production ready build.
  - Compile `.wpy` files to `.wxml` / `.js` / `.wxss` etc
  - Related NPM packages
  - Minified JavaScript
  - Copy static files



## Thanks


This repository relies on the [wepy](https://github.com/wepyjs/wepy),[友福图书馆](https://github.com/glore/library),[扇贝阅读](https://github.com/yshkk/shanbay-mina) thanks to the efforts of the author.
For detailed explanation & more functions, checkout the [微信官方小程序文档](https://mp.weixin.qq.com/debug/wxadoc/dev/api/) and [小程序框架wepy文档](https://wepyjs.github.io/wepy/).

This repository is forked form https://github.com/glore/library  Thanks  Ufutx, Glore

## Fork It And Make Your Own

You can fork this repo to create your own demo, and run it.



## LICENSE

[LICENSE](https://github.com/glore/library/LICENSE)

Please note that the open source protocol for this repository is **GPL**. This means that you have the freedom to run, copy, modify and distribute the software. However, this software your modified itself is bound by GPL.

**You must open the source code**

Copyright (c) 2018 - JusticeShi
