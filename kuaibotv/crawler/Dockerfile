FROM openjdk:8-jre-alpine

ADD ./crawler-1.0-SNAPSHOT-jar-with-dependencies.jar /

ENTRYPOINT ["java","-jar","/crawler-1.0-SNAPSHOT-jar-with-dependencies.jar"]

CMD ["tcp://activemq:61616","MSG","/data"]