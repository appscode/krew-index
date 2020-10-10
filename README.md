# krew-index
Krew index for kubectl plugins by AppsCode

## Install kubectl

https://kubernetes.io/docs/tasks/tools/install-kubectl/

## Install krew

https://krew.sigs.k8s.io/docs/user-guide/setup/install/

## Configure AppsCode krew-index

```bash
kubectl krew index add appscode https://github.com/appscode/krew-index.git
kubectl krew update
```

### Install Stash cli

```bash
kubectl krew install appscode/stash
kubectl stash -h
```

### Install KubeDB cli

```bash
kubectl krew install appscode/dba
kubectl dba -h
```

### Install KubeVault cli

```bash
kubectl krew install appscode/vault
kubectl vault -h
```
