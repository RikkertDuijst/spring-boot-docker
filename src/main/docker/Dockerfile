FROM openjdk

VOLUME /tmp
ADD maven/${project.artifactId}-${project.version}.${project.packaging} myapp.jar
RUN sh -c 'touch /myapp.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/myapp.jar"]
