# FROM confluentinc/cp-kafka-connect:5.4.1
FROM debezium/connect:1.0

COPY confluentinc-kafka-connect-jdbc-5.4.1/lib/*  /kafka/connect/kafka-connect-jdbc/
COPY confluentinc-kafka-connect-jdbc-5.4.1/etc/* /etc/

COPY mssql-jdbc-8.2.0.jre11.jar /kafka/connect/kafka-connect-jdbc/
