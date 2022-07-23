
查看当前登录的npm用户  
```
npm whoami
```
发布NPM包常用命令  
```
注册：npm adduser
初始化：npm init
登录：npm login （初次发包）
发包：npm publish
撤销包：npm unpublish 包名
删除包：npm deprecate 包名 [@版本] “描述”
查看当前账号：npm whoami
本地联调：npm link
取消本地联调：npm unlink
查看安装了多少包：npm ls
查看node安装路径：npm get prefix
查看全局node包：npm root -g
清理缓存：npm cache clean -f
```
发布包到NPM仓库(发私包是收费的)  
```
npm publish --access public
```
