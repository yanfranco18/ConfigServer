FROM openjdk:11.0-oracle
VOLUME /tmp
EXPOSE 8090
ADD ./target/config-server-0.0.1-SNAPSHOT.jar config-server.jar
ENTRYPOINT ["java","-jar","/config-server.jar"]