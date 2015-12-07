FROM tomcat

# Remove old webapps
RUN rm -rf /usr/local/tomcat/webapps/*

# Copy webapps content to deploy it on tomcat
COPY ./webapps/* /usr/local/tomcat/webapps

# Start tomcat
CMD ["catalina.sh", "run"]
