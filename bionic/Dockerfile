FROM ubuntu:bionic

RUN apt-get update \
 && apt-get -y install wget

RUN wget https://apt.puppetlabs.com/puppet-release-stretch.deb \
 && dpkg -i puppet-release-stretch.deb \
 && apt-get update \
 && apt-get -y install puppet
