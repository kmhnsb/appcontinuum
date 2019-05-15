FROM adoptopenjdk/openjdk8:jdk8u202-b08-alpine-slim
ADD applications/allocations-server/build/libs/allocations-server-1.0-SNAPSHOT.jar allocations-server-1.0-SNAPSHOT.jar
CMD ["java","-Djava.security.egd=file:/dev/./urandom", "-Dserver.port=${PORT}","-jar", "allocations-server-1.0-SNAPSHOT.jar"]