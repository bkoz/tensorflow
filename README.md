# tensorflow
Run Tensorflow on OpenShift
# Tensorflow/Tensorboard on OpenShift

oc adm policy add-scc-to-user privileged -z default -n nvidia-device-plugin

oc create -f tensorflow-template.yaml

oc new-app tensorflow

### ToDo

Build a tensorflow image based on RHEL or Centos


