FROM ubuntu:xenial

RUN apt-get update \
 && apt-get -y install wget

RUN wget https://apt.puppetlabs.com/puppet-release-xenial.deb \
 && dpkg -i puppet-release-xenial.deb \
 && apt-get update \
 && apt-get -y install puppet
