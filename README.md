# zhuye_kim_HTML

> 🏠 每次打开浏览器都是回家

仿 zhuye.kim 的简单导航主页 written in PURE HTML

## 效果展示

[Based on GitHub Page](https://idealclover.github.io/zhuye_kim_HTML/)

[Based on my website](https://index.idealclover.cn/)

![1](/pics/1.png)

![2](/pics/2.png)

## 功能特性

* 无后台，数据以json形式存储
* 即开即用，不需要任何其他环境，能部署HTML的地方都可以用
* 支持GitHub Page，一键fork并搭建

## 如何部署

### GitHub Page 方案

~~star⭐并~~fork🍴本项目，在setting中开启github page🏠并访问所提供的链接🔗

修改数据则通过修改并merge完成

### 本地化部署方案

下载该项目的zip包并部署在公共服务器上，访问服务器相关资源

## 目录介绍

/data文件夹存放相关数据

```
data/
│  bglist.json		- 背景图片分类信息
│  category.json    	- 分类信息
│
├─bgdetails
│      data_1.json	- 背景图片某分类下具体图片信息
│
├─bgimgs
│      1.png		- 背景图片
│
├─bgpreviews
│      1.png		- 背景图片预览
│
└─details
        data_1.json	- 链接信息，序号为分组id
```

## Contribute

如果有任何想法或需求，可以在 issue 中告诉我们，同时我们欢迎各种 pull requests

## Thanks

Thanks to [wenguonideshou/zhuye_kim](https://github.com/wenguonideshou/zhuye_kim).
