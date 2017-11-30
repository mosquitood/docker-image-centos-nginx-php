# 基于centos7的nginx&php的docker镜像
- centos 7
- nginx  1.12.1
- php 5.6.31
- supervisor 3.3.3
- 暴露端口 80 443 9000
- 工作目录 /data/wwwroot
- 数据卷 
  1. /data/wwwroot
  2. /data/wwwlogs
- nginx配置 
  1. 安装目录 -> /usr/local/nginx
  1. nginx.conf -> /usr/local/nginx/conf/nginx.conf
  2. rewrites -> /usr/local/nginx/conf/rewrite
  3. vhosts -> /usr/local/nginx/conf/vhosts
 - php 
  1. 安装目录 -> /usr/local/php
  2. php.ini -> /usr/local/php/etc/php.ini
  3. php-fpm.conf -> /usr/local/php/etc/php-fpm.conf
