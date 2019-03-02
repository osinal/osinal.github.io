---
layout: post
title:  "Seafile 日志时间错误"
categories: linux
tags:  centos7 linux IT运维 Seafile 
author: osInal
---

* content
{:toc}


## 原因

今日发现Seafile日志时间不正确

```
## 解决方法：

>  

```js
cd /var/www/seafile/conf
vi seahub_settings.py
TIME_ZONE = 'Asia/Shanghai' #增加时区
:wq

```

------









