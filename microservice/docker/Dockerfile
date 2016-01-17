FROM jboss/apiman-wildfly

ADD everest-1.0-SNAPSHOT.war /opt/jboss/wildfly/standalone/deployments/
ADD catalog.war /opt/jboss/wildfly/standalone/deployments/
ADD order.war /opt/jboss/wildfly/standalone/deployments/
ADD user.war /opt/jboss/wildfly/standalone/deployments/
ADD everest-web.war /opt/jboss/wildfly/standalone/deployments/
ADD sample.war /opt/jboss/wildfly/standalone/deployments/

#MAINTAINER Arun Gupta <arungupta@redhat.com>
#
#ADD microservice /opt/jboss/wildfly/microservice
#
#CMD ["/opt/jboss/wildfly/microservice/create-resources.sh"]