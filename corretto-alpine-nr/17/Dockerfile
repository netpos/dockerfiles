FROM amazoncorretto:17-alpine-jdk

RUN wget http://download.newrelic.com/newrelic/java-agent/newrelic-agent/current/newrelic-java.zip -P /tmp/ \
    && unzip /tmp/newrelic-java.zip -d /opt/ \
    && rm /tmp/newrelic-java.zip