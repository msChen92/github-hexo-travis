# github-hexo-travis
需要两个配置文件
完整流程：
1.hexo初始化项目： hexo init msChen
2. cd  msChen
本地预览： hexo  server
3.把hexo 网站源码推送到hub仓库中 hexo分支
git init 
git add --all
git commit -m ""
git remote add origin "git@github.com:msChen92/msChen92.github.io.git"
git push origin master:hexo
