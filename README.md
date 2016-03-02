# dockerstack-nginx-php7-myql
docker stack configuration for nginx php7 and mysql services

php7 nginx mysql docker 容器开发环境

使用方法
git clone https://github.com/stevenyesz/dockerstack-nginx-php7-myql.git
在dockerstack-nginx-php7-myql 目录下执行
docoker-compose up -d
然后访问 http://[ip-docker-machine]/
默认是 phpinfo()的输出。

mysql_data 为数据库持久化文件目录
webroot 为网站根目录
