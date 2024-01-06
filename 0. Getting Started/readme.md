# Getting Started

## Linux (VM or WSL)

> If you are running iptables in nftables mode instead of legacy you might encounter issues. We recommend utilizing newer iptables (such as 1.6.1+) to avoid issues.
> ```bash
> sudo update-alternatives --set iptables /usr/sbin/iptables-legacy
> ```

> You may need to disable IPv6 if running in WSL2. Add the following to **.wslconfig** in your **User** directory
>
> ```text
> [wsl2]
> kernelCommandLine=ipv6.disable=1
> ```

1. Download K3s v1.29.0+k3s1 from https://github.com/k3s-io/k3s/releases/tag/v1.29.0%2Bk3s1 on **your x64 VM/WSL instance**
```shell
wget https://github.com/k3s-io/k3s/releases/download/v1.29.0%2Bk3s1/k3s
```
or if running **arm64**
```shell
wget https://github.com/k3s-io/k3s/releases/download/v1.29.0%2Bk3s1/k3s-arm64
```
2. Add execute modifier to `k3s`
```shell
chmod +x k3s
```
3. Run `k3s` as `root` with `server` argument
```shell
sudo ./k3s server
```
4. In another terminal, copy contents of `/etc/rancher/k3s/k3s.yaml`
```shell
cat /etc/rancher/k3s/k3s.yaml
```
5. Grab IP address of host
```shell
ip addr show
```



## k3d (Docker)

1. Download k3d (https://github.com/k3d-io/k3d/releases)
2. Create 2 node cluster
```shell
k3d cluster create codemash --agents 2 -p "8081:80@loadbalancer"
```
3. Grab kubeconfig
```shell
k3d kubeconfig get codemash
```



## OpenLens

1. Install OpenLens (https://github.com/MuhammedKalkan/OpenLens)
2. Open OpenLens and go to File > Add Cluster
3. Paste in contents of `/etc/rancher/k3s/k3s.yaml`
4. Install **@alebcay/openlens-node-pod-menu** extension from https://github.com/alebcay/openlens-node-pod-menu





