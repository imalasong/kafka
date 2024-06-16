background：
jdk17

1、modify server.properties file:

log.dirs:
zookeeper.connect

2、VM Options:
-Dkafka.logs.dir=/Users/xiaochangbai/workspaces/idea/kafka/logs 
-Dlog4j.configuration=file:/Users/xiaochangbai/workspaces/idea/kafka/config/log4j.properties

3、Program arguments:
/Users/xiaochangbai/workspaces/idea/kafka/config/server.properties