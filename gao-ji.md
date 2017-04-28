# 高级

## 架设本地服务器

* 坑之一，不要用Docker安装
  > 千万不要用Docker安装，因为gitbook的镜像做得不是很友好，按照官方的说明都会报错，而且MAC的服务器上容器的磁盘还不能映射到本地。

### node.js 环境搭建

* 略

### gitbook的安装

* 安装gitbook的包

```bash
npm install gitbook-cli -g
```

* 启动服务， 在git的项目里启动server，默认的浏览器端口是4000


```bash
 

gitbook serve

Live reload server started on port: 35729
Press CTRL+C to quit ...

warn: no summary file in this book
info: 7 plugins are installed
info: loading plugin "livereload"... OK
info: loading plugin "highlight"... OK
info: loading plugin "search"... OK
info: loading plugin "lunr"... OK
info: loading plugin "sharing"... OK
info: loading plugin "fontsettings"... OK
info: loading plugin "theme-default"... OK
info: found 1 pages
info: found 10 asset files
info: >> generation finished with success in 0.5s !

Starting server ...
Serving book on http://localhost:4000
```



