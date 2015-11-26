FROM baselibrary/python:2.7
MAINTAINER ShawnMa <qsma@thoughtworks.com>

ENV DEBIAN_FRONTEND noninteractive

## Packages
RUN \
  pip install shadowsocks==2.8.2

EXPOSE 8388

ENTRYPOINT ["/usr/local/bin/ssserver"]

