FROM --platform=linux/amd64 mysql:5.7

RUN yum install -y oracle-epel-release-el7 \
    && yum install -y pv \
    && yum clean all

EXPOSE 3306
