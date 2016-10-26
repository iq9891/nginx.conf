# nginx.conf
mac上面nginx配置，域名重定向

## 方法(mac)
1、 `brew install nginx`
2、 `sudo vim /usr/local/etc/nginx/nginx.conf`
3、 粘贴目录中nginx.conf文件的内容
4、 `sudo vim /etc/hosts`
5、 添加 `127.0.0.1       www.limenglong.com`
6、 `sudo nginx` 打开nginx服务器， `sudo nginx -s stop` 关闭nginx服务器
7、 如果遇到403，那么是静态文件夹权限不够，直接打开简介，添加admin用户
