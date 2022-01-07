# Getting Started
0. Open terminal on host Ubuntu system
1. Download K3s v1.22.5+k3s1 from https://github.com/k3s-io/k3s/releases/tag/v1.22.5%2Bk3s1 
```shell
wget https://github.com/k3s-io/k3s/releases/download/v1.22.5%2Bk3s1/k3s
```
2. Add execute modifier to `k3s`
```shell
chmod +x k3s
```
3. Run `k3s` as `root` with `server` argument
```shell
sudo ./k3s server
```
4. Copy contents of `/etc/rancher/k3s/k3s.yaml`
```shell
cat /etc/rancher/k3s/k3s.yaml
```
5. Grab IP address of host
```shell
ip addr show
```
6. Open Lens and go to File > Add Cluster
7. Paste in contents of `/etc/rancher/k3s/k3s.yaml`
8. Change HTTP address to IP address of host Ubuntu System