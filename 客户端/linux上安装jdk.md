- 在Oracle中下载linux版的jdk

- 通过ftp工具上传到服务器上

- 查看linux上有没有 ` rpm -qa|grep java`有没有自带jdk

- 然后解压我们上传的jdk文件`tar -zxvf jdk***`

- 配置环境变量（这里的/usr/local是解压的jdk路径）

  ``````java
  export JAVA_HOME=/usr/local/java/jdk1.8.0_171 
  export JRE_HOME=${JAVA_HOME}/jre  
  export CLASSPATH=.:${JAVA_HOME}/lib:${JRE_HOME}/lib  
  export  PATH=${JAVA_HOME}/bin:$PATH
  ``````

  执行 `source /etc/profile` 使配置文件生效

  执行`java -version` 检查重新安装的jdk