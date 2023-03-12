FROM openjdk:11

RUN curl http://download.newrelic.com/newrelic/java-agent/newrelic-agent/current/newrelic-java.zip -o /tmp/newrelic.zip \
    && unzip /tmp/newrelic.zip -d /opt/ \
    && rm /tmp/newrelic.zip

ENV NEW_RELIC_APPLICATION_LOGGING=false