FROM ubuntu:trusty

RUN apt-get update \
 && apt-get -y install wget

RUN wget https://apt.puppetlabs.com/puppet-release-trusty.deb \
 && dpkg -i puppet-release-trusty.deb \
 && apt-get update \
 && apt-get -y install puppet
