# web应用服务器

### web应用服务器:tomcat 、jetty、Jboos、weblogic

### 一、tomcat是什么？

----

Tomcat是一个servlet容器

servlet === server+applet；---服务端

java applet ---客服端

servlet>>>wrapper>>>context>>>host>>>engine (server.xml文件中可以看到这个层级结构)

![image-20191215120903458](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20191215120903458.png)



### 二、tomcat安装使用

---

从官网下载tomcat，解压

bin：存放各个平台启动和停止服务的脚本。（例如：startup.sh（linux）startup.bat（win））

conf：存放各种tomcat服务器的配置文件。（server.xml）

lib：存放各种jar包。

logs：存放tomcat服务运行的日志。

temp：存放tomcat运行时的临时文件。

webapps：存放允许客户度应用访问的资源。

work：tomcat将jsp转换之后的servlet文件。

