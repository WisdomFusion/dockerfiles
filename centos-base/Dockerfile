FROM centos:centos7
MAINTAINER WisdomFusion <WisdomFusion@gmail.com>

RUN yum -y update
RUN yum -y install man wget iptraf iotop htop vim-enhanced lrzsz bash-completion

RUN echo "alias vi='vim'" >> ~/.bashrc
RUN echo "set fencs=utf-8,ucs-bom,gb18030,gbk,gb2312,cp936" >> ~/.vimrc
RUN echo "set fileformats=unix,dos" >> ~/.vimrc

