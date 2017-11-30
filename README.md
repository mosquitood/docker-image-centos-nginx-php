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
- nginx
  1. /usr/local/nginx
  2. /usr/local/nginx/conf/nginx.conf
  3. /usr/local/nginx/conf/rewrite
  4. /usr/local/nginx/conf/vhosts
- php
  1. /usr/local/php
  2. /usr/local/php/etc/php.ini
  3. /usr/local/php/etc/php-fpm.conf
	
