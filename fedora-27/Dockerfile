FROM fedora:27

RUN yum -y install https://yum.puppet.com/puppet/puppet-release-fedora-27.noarch.rpm
RUN rpm --import /etc/pki/rpm-gpg/RPM-GPG-KEY-*
RUN yum -y install \
      puppet-agent
