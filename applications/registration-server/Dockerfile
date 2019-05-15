FROM adoptopenjdk/openjdk8:jdk8u202-b08-alpine-slim
ADD applications/registration-server/build/libs/registration-server-1.0-SNAPSHOT.jar registration-server-1.0-SNAPSHOT.jar
CMD ["java","-Djava.security.egd=file:/dev/./urandom", "-Dserver.port=${PORT}","-jar", "registration-server-1.0-SNAPSHOT.jar"]