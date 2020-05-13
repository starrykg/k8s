# k8s
learning k8s


概念：
1.一个master有一群node节点与之对应
2.master不存储容器，只负责调度、网关、控制器、资源对象存储
3.容器是存储在node节点内部的
4.pod内部可以有一个容器，或者是多个容器
5.kubelet负责本地的pod的维护
6.kube-proxy负责负载均衡，在多个pod之间来做
