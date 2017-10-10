FROM centos:7
RUN yum -y install https://rpms.remirepo.net/enterprise/remi-release-7.rpm
RUN yum -y install --enablerepo=remi-php54 php php-mysql php-mbstring php-dom
RUN yum -y install httpd
RUN systemctl enable httpd

ENTRYPOINT ["/sbin/init"]
