# 博客信息

- 搭建工具 : [hexo](https://hexo.io/)
- 使用主题 : [yilia](https://github.com/litten/hexo-theme-yilia)
- 更新流程
  ``` git
  cd /path/to/foregotto.github.io/ # 进入博客根目录
  git add .                        # 把更改内容加入暂存区
  git commit -m "some message"     # 提交内容更改
  git push origin hexo             # 更新远程仓库
  hexo g                           # 生成静态内容
  hexo d                           # 部署到指定仓库
  ```
