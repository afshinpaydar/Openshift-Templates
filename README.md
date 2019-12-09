# Openshift-Templates
oc process -f rabbitmq.yml  NAMESPACE="$(oc project --short)" | oc create -f -
