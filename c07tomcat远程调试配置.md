tomcat/conf下在startup 或catalina 
	SET CATALINA_OPTS=-server -Xdebug -Xnoagent -Djava.compiler=NONE -Xrunjdwp:transport=dt_socket,server=y,suspend=n,address=开放的调试接口
idea中 配置远程调试，ip，调试端口。关联上模块