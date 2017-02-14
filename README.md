项目常用操作：
    1.打包： 启动cfg文件中的dist.js
    2.创建主页： git subtree push --prefix=dist origin gh-pages

**package.json里的scripts： 如果不是默认的脚本 需要这样运行 npm run xxx。

**推送到远程分支： git push origin local_branch:remote_branch
这个操作，local_branch必须为你本地存在的分支，remote_branch为远程分支，如果remote_branch不存在则会自动创建分支。
类似，git push origin :remote_branch，local_branch留空的话则是删除远程remote_branch分支。
    