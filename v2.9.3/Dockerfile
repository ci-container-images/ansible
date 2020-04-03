FROM  registry.access.redhat.com/ubi8/ubi:latest

RUN  yum -y install git-core python3-pip  &&  \
    yum clean all

RUN pip3 install ansible==2.9.3 openshift==0.10.0 hvac==0.9.6 ansible-modules-hashivault==4.2.3 requests==2.22.0 ansible-lint

CMD ["/bin/bash"]