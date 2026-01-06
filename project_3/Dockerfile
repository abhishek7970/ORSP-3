FROM tomcat:9-jdk11

RUN rm -rf /usr/local/tomcat/webapps/*

# WAR inside subfolder
COPY ORSProject3/target/project_3.war /usr/local/tomcat/webapps/project_3.war

EXPOSE 8080
CMD ["catalina.sh", "run"]
