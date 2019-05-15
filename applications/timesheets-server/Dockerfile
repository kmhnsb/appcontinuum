FROM adoptopenjdk/openjdk8:jdk8u202-b08-alpine-slim
ADD applications/timesheets-server/build/libs/timesheets-server-1.0-SNAPSHOT.jar timesheets-server-1.0-SNAPSHOT.jar
CMD ["java","-Djava.security.egd=file:/dev/./urandom", "-Dserver.port=${PORT}","-jar", "timesheets-server-1.0-SNAPSHOT.jar"]