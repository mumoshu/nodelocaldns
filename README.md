# ndoelocaldns chart

[nodelocaldns](https://github.com/kubernetes/kubernetes/blob/master/cluster/addons/dns/nodelocaldns/nodelocaldns.yaml) is a Kubernetes daemonset for running node-local dns server for a more scalable Kubernetes cluster DNS.

## Getting Started

```console
$ helm repo add nodelocaldns-charts https://raw.githubusercontent.com/mumoshu/nodelocaldns/master/docs
$ helm install --name nodelocaldns nodelocaldns-charts/nodelocaldns
```
