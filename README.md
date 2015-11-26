## ThoughtWorks Docker Image: shadowsocks

[![](http://dockeri.co/image/baselibrary/shadowsocks)](https://registry.hub.docker.com/u/baselibrary/shadowsocks/)

### Base Docker Image

* `latest`: shadowsocks 2.8
* `2.8` : shadowsocks 2.8

### Installation

    docker pull baselibrary/shadowsocks

### Usage

    docker run -it --rm baselibrary/shadowsocks -s 0.0.0.0 -p 8388 -k password -m aes-256-cfb
