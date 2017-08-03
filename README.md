# kube-geth

Runs a geth node in a kubernetes cluster.


## Prerequisites

First provision a disk:

```console
  gcloud compute disks create --size=750GB geth-data
```

Now create the kubernetes resources:

```console
  kubectl create -f deploy/
```
