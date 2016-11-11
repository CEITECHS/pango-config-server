FROM openjdk:8
MAINTAINER Iddy Magohe
ENV spring.cloud.config.server.git.uri https://github.com/CEITECHS/pango-configs
EXPOSE 8888
ADD pango-config-server.jar app.jar
ENTRYPOINT [ "sh", "-c", "java -jar /app.jar" ]