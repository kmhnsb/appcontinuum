FROM adoptopenjdk/openjdk8:jdk8u202-b08-alpine-slim
ADD applications/discovery-server/build/libs/discovery-server-1.0-SNAPSHOT.jar discovery-server-1.0-SNAPSHOT.jar
CMD ["java","-Djava.security.egd=file:/dev/./urandom", "-Dserver.port=${PORT}","-jar", "discovery-server-1.0-SNAPSHOT.jar"]