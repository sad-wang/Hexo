---
title: npm换源
date: 2018/10/14
categories: npm
tags: npm
---
# **将 Npm 的源替换成淘宝的源**

在墙内久了，难免会碰到撞墙的时候，所幸国内也有众多 NPM 镜像可供选择，在大多数情况下我们可以使用国内的源（比如 [淘宝 NPM 镜像](http://npm.taobao.org/)）去替换官方的源以加快下载包的速度。

不过呢，我们在发布自己的包的时候却需要将源修改回官方的 https://registry.npmjs.org/ 源。

## **修改源地址为淘宝 NPM 镜像**

```bash
npm config set registry <http://registry.npm.taobao.org/>
```

## **修改源地址为官方源**

```bash
npm config set registry <https://registry.npmjs.org/>
```

