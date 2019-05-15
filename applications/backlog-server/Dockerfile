FROM adoptopenjdk/openjdk8:jdk8u202-b08-alpine-slim
ADD applications/backlog-server/build/libs/backlog-server-1.0-SNAPSHOT.jar backlog-server-1.0-SNAPSHOT.jar
CMD ["java","-Djava.security.egd=file:/dev/./urandom", "-Dserver.port=${PORT}","-jar", "backlog-server-1.0-SNAPSHOT.jar"]