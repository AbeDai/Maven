### 简介
主要是作为Maven仓库的git管理仓库。将本地代码打包成maven结构，提交到当前远程仓库。搭建文件服务器，在服务器中更新仓库，实现Maven资源的访问效果。

### 使用介绍
以mac开发环境为例
- 在本机的/Users/userName/.customM2目录下，建立本地仓库
- 将本地代码以maven结构同步到.customM2目录下，并同步到远程仓库
- 在服务器中，同步git仓库
- 通过 **http://maven.daiyibo.cn** 直接访问资源文件了
