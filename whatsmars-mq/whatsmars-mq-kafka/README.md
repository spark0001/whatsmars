# [Kafka](https://github.com/apache/kafka):

Please walk to `whatsmars-boot-sample-kafka`

linux:<br>
启动zk ./zookeeper-server-start.sh ../config/zookeeper.properties<br>
启动server ./kafka-server-start.sh ../config/server.properties<br>

win:<br>
修改bin/windows/kafka-server-start.bat set KAFKA_HEAP_OPTS=-Xmx512M -Xms512M<br>
server.properties port=9092<br>
启动zk zookeeper-server-start.bat ../../config/zookeeper.properties<br>
启动server kafka-server-start.bat ../../config/server.properties<br>

[kafka原理与特性](https://blog.csdn.net/javahongxi/article/details/85109383)
