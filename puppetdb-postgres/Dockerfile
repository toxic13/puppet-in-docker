FROM postgres:9.5.3
MAINTAINER Gareth Rushgrove "gareth@puppet.com"

LABEL org.label-schema.vendor="Puppet" \
      org.label-schema.url="https://github.com/puppetlabs/puppet-in-docker" \
      org.label-schema.name="PostgreSQL instance for PuppetDB" \
      org.label-schema.license="Apache-2.0" \
      org.label-schema.version="0.1.0" \
      org.label-schema.vcs-url="https://github.com/puppetlabs/puppet-in-docker" \
      org.label-schema.vcs-ref="a2b1fbbc73177ddc3def23d167f9beb9c3ef9f6c" \
      org.label-schema.build-date="2017-02-21T17:25:14Z" \
      org.label-schema.schema-version="1.0" \
      com.puppet.dockerfile="/Dockerfile"

COPY docker-entrypoint-initdb.d /docker-entrypoint-initdb.d

COPY Dockerfile /
