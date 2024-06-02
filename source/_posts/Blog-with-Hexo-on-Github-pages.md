---
title: Blog with Hexo on Github pages
date: 2024-06-02 21:18:21
tags: blogging, hexo
---

## What is hexo and why should we use it

Hexo is a simple, lightweight and fast blogging framework that can be used to host your blog in your own server under your own domain. In Hexo we have to use [Markdown](https://hexo.io/) files to feed content to your blog articles.

## Prerequisites

1.  Node Js (Recommends 12.0 or higher) with NPM
2.  GIT
3.  GitHub Account

#### Git installation

1. For windows Installer
2. For Mac Installer

> For mac and linux command "sudo apt-get install git-core"

## Hexo installation

Once all the requirements are installed, you can install Hexo with npm using bellow command. It will install hexo globally in your local machine.

```
$ npm install -g hexo-cli
```

## Setup your static content site

Once hexo was installed run follwing commads to initialize hexo setup in your target folder. This folder will be your website source.

```
$ cd <target folder>
$ hexo init
$ npm install
```

## Start blogging

#### Create a new article

```
$ hexo new "My New Post"
```

For more [Information](https://hexo.io/docs/writing.html)

#### Generate static files

```
$ hexo G
```

For more [Information](https://hexo.io/docs/generating.html)

#### Run local server

```
$ hexo S
```

For more [Information](https://hexo.io/docs/server.html)
