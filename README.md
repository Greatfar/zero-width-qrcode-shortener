# 说明
#程序演示:
<br>
https://ml.mk
<br><br>
安装:
<br>
1.解压本程序到域名根目录
<br>
2.修改config.php，sqlite需保证数据库可写(chmod 666 urls.sqlite;chown www:www urls.sqlite)
<br>
3.配置伪静态，详情查看nginx.conf或.htaccess
<br><br>
默认使用sqlite文本数据库，访问量大请自行修改为oracle、mysql或关闭日志记录
<br>
phpliteadmin.php为第三方单文件sqlite管理程序，默认中文，密码admin
<br><br>
20191107 感谢各位支持，演示站结束测试并正式上线，现已升级到oracle数据库，之前链接均已保留可正常访问。
<br>
另python版暂不发布(兼容的云太多一堆bug，有时间再弄，不作时间保证)
