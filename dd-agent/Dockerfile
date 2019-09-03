FROM datadog/docker-dd-agent

RUN apt-get update
RUN apt-get install -y less telnet vim

ADD ./datadog.yaml /etc/datadog-agent/datadog.yaml
