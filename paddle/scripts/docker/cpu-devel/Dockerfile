FROM ubuntu/ubuntu:14.04
MAINTAINER PaddlePaddle Dev Team <paddle-dev@baidu.com>
COPY build.sh /root/
ENV WITH_GPU=OFF
ENV IS_DEVEL=ON
ENV WITH_DEMO=OFF
ENV PIP_INSTALL_ARGS ""
ENV PIP_GENERAL_ARGS ""
RUN cd /root/ && bash build.sh
