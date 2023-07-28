This repository holds a Helm chart to deploy vcluster in HA with k3s and an external etcd data store.

The chart deploys both etcd and and vcluster with 3 replicas by default.

Usage:
```
helm install  rel-vcluster ./vcluster -n my-vcluster -f values_etcd_external.yaml
```

The chart is based on vcluster upstream chart version 0.15.2
