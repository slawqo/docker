FROM centos

# Add EPEL repository
RUN yum install -y https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
# Install necessary packages
RUN yum group install -y "Development Tools"
RUN yum install -y python-pip python-wheel python-devel
RUN yum install -y openssl openssl-devel
RUN pip install tox
