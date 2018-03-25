FROM centos
MAINTAINER GUAN
ENV HOME /root
ENV JDK_RPM jdk-8u161-linux-x64.rpm 
WORKDIR ${HOME}
RUN yum update -y &&\
    yum install -y vim curl wget  &&\
     wget --no-check-certificate -c --header "Cookie: oraclelicense=accept-securebackup-cookie" \
          http://download.oracle.com/otn-pub/java/jdk/8u161-b12/2f38c3b165be4555a1fa6e98c45e0808/${JDK_RPM} &&\
     yum localinstall -y ${JDK_RPM} &&\
     java -version && \
     rm ${JDK_RPM}
CMD ["pwd"]

