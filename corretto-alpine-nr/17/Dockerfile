FROM amazoncorretto:17-alpine-jdk

ENV NEW_RELIC_APPLICATION_LOGGING=false

RUN wget http://download.newrelic.com/newrelic/java-agent/newrelic-agent/current/newrelic-java.zip -P /tmp/ \
    && unzip /tmp/newrelic-java.zip -d /opt/ \
    && rm /tmp/newrelic-java.zip