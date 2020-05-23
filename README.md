# [Scrapy 生态学习笔记](https://pegasuswang.github.io/LetsGo/)


## 目的

scrapy 也是爬了不少网站了，写这个的目的是对scrapy框架的一个总结，然后就是对自己复习吧！并没有
想写的非常深入，因为本身技术一般，但对以后继续深入或者说改造业务也是有所帮助的。




您可以在以下地址阅读：

- 阅读地址：[    https://jusk9527.github.io/LetsScrapy/ ](https://jusk9527.github.io/LetsScrapy/)
- 本项目地址：[   https://github.com/jusk9527/LetsScrapy ](https://github.com/jusk9527/LetsScrapy)


## 工具

- 开发环境
mac
- Pycharm2019



## 本电子书制作和写作方式
使用 mkdocs 和 markdown 构建，使用 Python-Markdown-Math 完成数学公式。
markdown 语法参考：http://xianbai.me/learn-md/article/about/readme.html

安装依赖：

```sh
pip install mkdocs    # 制作电子书, http://markdown-docs-zh.readthedocs.io/zh_CN/latest/
# https://stackoverflow.com/questions/27882261/mkdocs-and-mathjax/31874157
pip install https://github.com/mitya57/python-markdown-math/archive/master.zip

# 建议直接安装 requirements.txt 中的依赖。已经锁定了版本，不同的 mkdocs 之间有一定差异
pip install -r requirements.txt

# 如果你 fork 了本项目，可以定期拉取主仓库的代码来获取更新，目前还在不断更新相关章节
```

你可以 clone 本项目后在本地编写和查看电子书：

```sh
mkdocs serve     # 修改自动更新，浏览器打开 http://localhost:8000 访问
# 数学公式参考 https://www.zybuluo.com/codeep/note/163962
mkdocs gh-deploy    # 部署到自己的 github pages
# 给 mkdocs 增加 gitalk 评论系统 https://50u1w4y.github.io/site/misc/gitalkBuild/
```


## 参考链接


[崔大](https://python3webspider.cuiqingcai.com/)

[mkdocs用法](https://www.xncoding.com/2020/03/01/tool/mkdocs.html)

## 勘误

本系列均来自笔者日常学习和工作总结，疏漏之处在所难免，如果文章或者视频有误，您可以到本项目 github 仓库或者文章评论区指出，欢迎批评指正。
笔者会认真对待并且修复错误。
