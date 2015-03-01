# agileframework.github.io
agileframework.org

## 怎样将域名绑定到github pages 博客上

* 1.在仓库根目录添加CNAME文件，在文件中添加域名（不带http，www等前缀），例如 z.cn
* 2.ping username.github.io记录下IP地址
* 3.使用账户登录dnspod，在dnspod中添加DNS serveice记录。   添加域名，设置两个A记录，分别是@和www，ip地址填上通过ping获取的IP地址。
* 4.等待解析成功即可
