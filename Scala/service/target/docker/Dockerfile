FROM openjdk
WORKDIR /opt/docker
ADD opt /opt
RUN ["chown", "-R", "daemon:daemon", "."]
EXPOSE 8081
USER daemon
ENTRYPOINT ["sh", "-c", "bin/example-service"]
CMD []
