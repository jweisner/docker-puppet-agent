FROM debian:jessie

RUN apt-get update \
 && apt-get -y install wget

RUN wget https://apt.puppetlabs.com/puppet5-release-jessie.deb \
 && dpkg -i puppet5-release-jessie.deb \
 && apt-get update \
 && apt-get -y install puppet-agent
ENV PATH /opt/puppetlabs/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
