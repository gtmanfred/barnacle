FROM fedora:24

COPY base.txt /base.txt
COPY dev_python27.txt /dev_python27.txt

RUN dnf -y install wget gcc git redhat-rpm-config salt-master salt-minion salt-ssh salt-syndic salt-cloud salt-api python-pip python-devel

RUN pip install -r /dev_python27.txt

VOLUME /testing
