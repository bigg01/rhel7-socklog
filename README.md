## rhel7-socklog

This repository creates a syslog listener on the specified UDP port **SYSLOG_PORT**

The listener is based on socklog http://smarden.org/socklog/socklog.8.html

## openshift

oc new-app https://github.com/git001/rhel7-socklog.git

## openshift template

oc process -f https://raw.githubusercontent.com/git001/rhel7-socklog/master/rhel7-socklog.yaml | oc create -f -