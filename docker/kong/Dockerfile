FROM kong:2.3.0-centos

LABEL description="kong with plugins"

USER root

RUN yum install -y git unzip && yum clean all

RUN luarocks install kong-oidc
