FROM openjdk:8-jre
LABEL maintainer="sealabaq"

COPY target/microservice-demo-items-0.0.1-SNAPSHOT.jar /app/
ENTRYPOINT ["/usr/bin/java"]
CMD ["-DITEMS_SERVICE_PORT=5566", "-Xmx64m", "-jar", "/app/microservice-demo-items-0.0.1-SNAPSHOT.jar"]

EXPOSE 5566
