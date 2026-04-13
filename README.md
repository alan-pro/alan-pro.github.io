# 学文の博客🥝

本站采用Hexo+Github搭建个人博客，采用Fomalhaut博主的模板，在此表示感谢🥰！

欢迎访问https://wenblog.top/



#  Hexo部署命令
Git push 到 GitHub,触发 CI 部署的话，本地不需要跑 hexo deploy，CI会自动执行这三步。
```shell
hexo cl || hexo clean  # 清理缓存
hexo g || hexo generate  # 生成静态资源
hexo d || hexo deploy # 部署
```



