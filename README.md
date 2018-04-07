# Yii2-advanced

>1. 解压文件

~~~sql
$ tar zxvf 2.0.14.tar.gz
~~~

>2.配置nginx文件

~~~sql
$ lnmp vhost add

a. 域名： backend.yii.net
   后台指向 /home/wwwroot/default/yii2-app-advanced-2.0.14/backend/web

b. 域名：frontend.yii.net
   前台指向  /home/wwwroot/default/yii2-app-advanced-2.0.14/frontend/web
~~~

>3.初始化开发文件

~~~sql
#在目录文件夹下执行 init
$ ./init

#开发环境选择Dev
~~~

>4.修改 .user.ini

~~~sql
# 多加一级 /home/wwwroot/default/yii2-app-advanced-2.0.14/

# frontend/web下的 .user.ini
open_basedir=/home/wwwroot/default/yii2-app-advanced-2.0.14/frontend/web:/home/wwwroot/default/yii2-app-advanced-2.0.14/:/tmp/:/proc/

# backend/web下的 .user.ini
open_basedir=/home/wwwroot/default/yii2-app-advanced-2.0.14/backend/web:/home/wwwroot/default/yii2-app-advanced-2.0.14/:/tmp/:/proc/
~~~

>5.本地配置 hosts

~~~sql
192.168.1.101 frontend.yii.net

192.168.1.101 backend.yii.net
~~~


>6.浏览器 地址栏访问

~~~sql
 congration!!!
~~~
