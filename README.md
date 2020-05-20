# Benchmarking performance on Azure cluster

In this article we will try to benchmark the performance of kubernetes without service mesh injection, Consul, Linkerd, and Istio service meshes.

#Cluster infos:
The cluster that we are using is an Azure cluster AKS, Here is informations about our cluster :
- Cluster's **datacenter Region** : **East Us**
- Cluster contains ** 2 Nodes **
  Each node with 2 CPUs, 7 Memory
  Total: **Core 4 vCPUs** and **Memory 14 GiB**

<p align="center">
<img src="docs/img/cluster-capacity.JPG"/>
</p>
  
#Benchmarking tool:
In our case, we are using **Fotio** as a benchmarking tool.
https://github.com/fortio/fortio

