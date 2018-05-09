FROM debian:wheezy

RUN apt-get update \
 && apt-get -y install \
    wget \
    ca-certificates

RUN wget https://apt.puppetlabs.com/puppet5-release-wheezy.deb \
 && dpkg -i puppet5-release-wheezy.deb \
 && apt-get update \
 && apt-get -y install \
    puppet-agent

ENV PATH /opt/puppetlabs/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
