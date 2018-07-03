# dubbo-learning-notes

### dubbo-admin安装

1 下载 dubbo-admin-2.6.0.war，自己找资源啦，比如csdn,百度网盘<br>
2 将该war包放到Tomcat目录下的webapps下，启动tomcat，会出现解压包<br>
3 找到路径 E:\tomcat\apache-tomcat-7.0.40\webapps\dubbo-admin-2.6.0\WEB-INF\WEB-INF下的dubbo.properties文件，修改zookeper后面的ip为自己   的ip 如下：dubbo.registry.address=zookeeper://127.0.0.1:2181<br>
4 启动tomcat <br>
5 浏览器访问：http://localhost:8888/dubbo-admin-2.6.0 即可。 （注：此处我的tomcat端口为8888） <br>
6 输入用户名：root 密码：root<br>

参考资料：https://blog.csdn.net/u011019141/article/details/79685511<br>
