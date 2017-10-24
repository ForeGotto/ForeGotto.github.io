这是用 [hexo](https://hexo.io/) 搭建的个人博客，使用的主题是 [yilia](https://github.com/litten/hexo-theme-yilia)。
主分支用于存储发布后的静态网页与资源，hexo 分支用于存储原始资源。
更新博客时工作流程如下：
```git
# 在仓库根目录下
git add .
git commit -m "some message"
git push origin hexo
hexo d
```