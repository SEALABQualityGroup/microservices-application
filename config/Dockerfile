FROM openjdk:8-jre
LABEL maintainer="sealabaq"

COPY target/microservice-demo-config-0.0.1-SNAPSHOT.jar /app/
ENTRYPOINT ["/usr/bin/java"]
CMD ["-Xmx64m", "-jar", "/app/microservice-demo-config-0.0.1-SNAPSHOT.jar"]

EXPOSE 8888
