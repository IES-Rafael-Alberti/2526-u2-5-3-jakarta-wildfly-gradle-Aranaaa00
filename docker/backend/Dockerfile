FROM quay.io/wildfly/wildfly:latest
COPY build/libs/crud-file.war /opt/jboss/wildfly/standalone/deployments/
CMD ["/opt/jboss/wildfly/bin/standalone.sh", "-b", "0.0.0.0"]
