FROM prod.registry.devshift.net/osio-prod/base/pcp:latest

RUN yum install -y valgrind httpd-tools hmaccalc strace \
    http://mirror.centos.org/centos/7.4.1708/paas/x86_64/openshift-origin/origin-clients-3.6.1-1.0.008f2d5.x86_64.rpm \
    && yum clean all
