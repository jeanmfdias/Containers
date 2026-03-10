FROM mysql:8.4

RUN microdnf install -y oracle-epel-release-el9 \
    && microdnf install -y pv \
    && microdnf clean all

EXPOSE 3306
