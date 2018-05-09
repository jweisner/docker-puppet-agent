FROM centos:6

RUN yum -y install https://yum.puppet.com/puppet/puppet-release-el-6.noarch.rpm
RUN rpm --import /etc/pki/rpm-gpg/RPM-GPG-KEY-*
RUN yum -y install \
      puppet-agent
