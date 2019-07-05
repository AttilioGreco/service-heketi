Automium Service: kubernetes 
======================================

[![Build Status](https://travis-ci.org/automium/service-kubernetes.svg?branch=master)](https://travis-ci.org/automium/service-heketi)

this project is meant to be used by [automium provisioner](https://github.com/automium/provisioner)

## variables

### Gluster

setup service var:
```
export SERVICE=automium/service-kubernetes
export MASTER=true
export NODE=true
export ETCD=true
export RANCHER_URL=http://rancher.local
export RANCHER_CLUSTER_TOKEN=237dh928gd2
export AUTOMIUM_AUTOSCALER_KUBECONFIG=YPBpVmVyq2lvbjogdjEKY2x1c3...RlWTFVMjU2Vkc1Q2RYTjZVMGhpYm1wUfo=
```

and follow the guide [here](https://github.com/automium/provisioner/blob/master/README.md#guide)
# service-heketi
