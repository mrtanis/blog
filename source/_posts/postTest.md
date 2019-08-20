---
title: postTest
date: 2019-08-20 14:12:02
categories:
- [cat1]
- [cat2]
tags:
- tag1
- tag2
---

#### 写个文章
* 第一点
* 第二点
二、配置Github
建库、同步本地什么的都是github基础操作，注意一点，建两个分支，master分支和对应源码，gh-pages分支作为hexo生成的静态页面上传分支。网上很多都说要用到xxx.github.io这个项目的，其实没必要，只需要推到其他分支即可，然后在setting里配置要作为页面显示的是哪个分支即可。
<!-- more -->

三、使用NexT主题
这个可以参考Next帮助文档，步骤说明很详细。

其中需要注意的点：

就是上边说的hexo-util的问题，已给出解决办法。
关于语言的问题，v5.1.x版本的中文是zh-Hans，而v6.0.0的中文是zh-CN，注意区分。
关于主题的配置文件，采用了Hexo data files特性，利用这个特性，可以放心更新next主题，而不担心配置丢失或烦于合并。
v6.0.0的fancybox移至外部仓库依赖，所以需要自行添加，添加方法参见详细安装步骤。
四、配置Travis CI
重点来了，详细步骤可参考用 Travis CI 自动部署 hexo，作者已经说的比较详细。

需要注意的一点是：在package.json中增加depoly的命令行语句，防止travis在自动执行到npm run deploy这一步的时候报找不到该script的错。
二、配置Github
建库、同步本地什么的都是github基础操作，注意一点，建两个分支，master分支和对应源码，gh-pages分支作为hexo生成的静态页面上传分支。网上很多都说要用到xxx.github.io这个项目的，其实没必要，只需要推到其他分支即可，然后在setting里配置要作为页面显示的是哪个分支即可。

三、使用NexT主题
这个可以参考Next帮助文档，步骤说明很详细。

其中需要注意的点：

就是上边说的hexo-util的问题，已给出解决办法。
关于语言的问题，v5.1.x版本的中文是zh-Hans，而v6.0.0的中文是zh-CN，注意区分。
关于主题的配置文件，采用了Hexo data files特性，利用这个特性，可以放心更新next主题，而不担心配置丢失或烦于合并。
v6.0.0的fancybox移至外部仓库依赖，所以需要自行添加，添加方法参见详细安装步骤。
四、配置Travis CI
重点来了，详细步骤可参考用 Travis CI 自动部署 hexo，作者已经说的比较详细。

需要注意的一点是：在package.json中增加depoly的命令行语句，防止travis在自动执行到npm run deploy这一步的时候报找不到该script的错。
二、配置Github
建库、同步本地什么的都是github基础操作，注意一点，建两个分支，master分支和对应源码，gh-pages分支作为hexo生成的静态页面上传分支。网上很多都说要用到xxx.github.io这个项目的，其实没必要，只需要推到其他分支即可，然后在setting里配置要作为页面显示的是哪个分支即可。

三、使用NexT主题
这个可以参考Next帮助文档，步骤说明很详细。

其中需要注意的点：

就是上边说的hexo-util的问题，已给出解决办法。
关于语言的问题，v5.1.x版本的中文是zh-Hans，而v6.0.0的中文是zh-CN，注意区分。
关于主题的配置文件，采用了Hexo data files特性，利用这个特性，可以放心更新next主题，而不担心配置丢失或烦于合并。
v6.0.0的fancybox移至外部仓库依赖，所以需要自行添加，添加方法参见详细安装步骤。
四、配置Travis CI
重点来了，详细步骤可参考用 Travis CI 自动部署 hexo，作者已经说的比较详细。

需要注意的一点是：在package.json中增加depoly的命令行语句，防止travis在自动执行到npm run deploy这一步的时候报找不到该script的错。
二、配置Github
建库、同步本地什么的都是github基础操作，注意一点，建两个分支，master分支和对应源码，gh-pages分支作为hexo生成的静态页面上传分支。网上很多都说要用到xxx.github.io这个项目的，其实没必要，只需要推到其他分支即可，然后在setting里配置要作为页面显示的是哪个分支即可。

三、使用NexT主题
这个可以参考Next帮助文档，步骤说明很详细。

其中需要注意的点：

就是上边说的hexo-util的问题，已给出解决办法。
关于语言的问题，v5.1.x版本的中文是zh-Hans，而v6.0.0的中文是zh-CN，注意区分。
关于主题的配置文件，采用了Hexo data files特性，利用这个特性，可以放心更新next主题，而不担心配置丢失或烦于合并。
v6.0.0的fancybox移至外部仓库依赖，所以需要自行添加，添加方法参见详细安装步骤。
四、配置Travis CI
重点来了，详细步骤可参考用 Travis CI 自动部署 hexo，作者已经说的比较详细。

需要注意的一点是：在package.json中增加depoly的命令行语句，防止travis在自动执行到npm run deploy这一步的时候报找不到该script的错。