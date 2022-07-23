初始化npm包信息
```
npm init
```

查看当前登录的npm用户  
```
npm whoami
```
发布NPM包常用命令  
```
npm adduser  // 注册npm用户
npm init  // 初始化npm包配置，生成package.json
npm login  // npm用户登录  

npm publish  // 发布npm包
npm unpublish 包名   // 撤销发布包  

npm deprecate 包名 [@版本] “描述”  // 删除包
npm ls  // 查看安装了哪些包
npm get prefix  // 查看包安装路径
npm root -g  // 查看全局node包
npm cache clean -f  // 清理缓存  

npm link  // 本地联调
npm unlink  // 取消本地联调
```
发布包到NPM仓库(发私包是收费的)  
```
npm publish --access public
```
