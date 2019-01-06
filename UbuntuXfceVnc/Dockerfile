FROM ubuntu

RUN apt update
RUN apt install -y wget net-tools bzip2 locales
RUN locale-gen en_US.UTF-8
RUN apt install -y ttf-wqy-zenhei
RUN wget -qO- https://dl.bintray.com/tigervnc/stable/tigervnc-1.9.0.x86_64.tar.gz | tar xz --strip 1 -C /
RUN apt install -y xfce4 xfce4-terminal