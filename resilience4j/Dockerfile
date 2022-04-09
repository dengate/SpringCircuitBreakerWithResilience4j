FROM openjdk:16-alpine3.13
MAINTAINER ahmet
COPY ["target/circuitbreaker-0.0.1-SNAPSHOT.jar", "target/"]
CMD ["nohup","java","-Dserver.port=9010","-jar","target/circuitbreaker-0.0.1-SNAPSHOT.jar"]
