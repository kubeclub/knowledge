[toc]

# Kubernetes
## 组件
### 核心组件
- etcd
- kube-apiserver
- kube-controller-manager
- kube-scheduler
- kube-proxy
- docker

### 附件组件
- DNS
    - kube-dns
    - coredns
- Ingress Controller
    - traefik
    - Nginx Plus
    - HAProxy Ingress
    - AppsCode Voyager
    - contour
    - Cloudflare Warp Ingress
    - F5 Big IP Controller
    - Gloo
    - gRPC Load balancing
    - Kong
    - nghttpx Ingress Controller
    - Ambassador
    - Skipper
- Heapster
- Dashboard
- Kubernator
- Federation
- eventrouter

### 资源对象
- Pod
    - Init Container
    - Pod Security Policy
    - Pod Lifecycle
    - Pod Hook
    - Pod Preset
    - Disruption
    - Resource Quota
    - Liveness 和 Readiness
- 集群配置
    - Node
    - Namespace
    - Label
    - Annotation
    - Taint/Toleration
    - Affinity/anti-affinity
    - Garbage Collection
- 控制器
    - Deployment
    - DaemonSet
    - StatefulSet
    - ReplicaSet
    - Job
    - CronJob
    - Horizontal Pod Autoscaling
    - cron-hpa-controller
    - Escalator

- 服务发现
    - Service
    - Ingress
- 身份与权限控制
    - Service Account
    - Network Policy
        - kubernetes-network-policy-recipes
    - Security Context
    - RBAC
- 存储配置
    - secret
    - configmap
    - volume
    - persistent volume
    - local volume
    - storage class
    - stork

- API 扩展
    - customresourceDefinition(CRD)
    - operator
        - awesome-operators
        - prometheus
        - confluent operator
        - kong api
        - kubernetes operators
        - k8s operator workshop
        - cert operator
        - cert manager
        - operator kit
        - container linux update operator
        - db operator
        - etcd
        - elasticsearch
        - memcached
        - mongoDB
        - mysql operator
        - postgreSQL
        - another postgreSQL
        - kafka
        - envoy operator
        - rbac-manager
        - akrobateo
    - aggregated api server
    - custom-metrics-apiserver-ingress-nginx
    - metacontroller

### 部署配置
- 单机部署
    - minikube
    - kind
    - kubeasz
    - sealos
- 集群部署
    - kubeadm
    - sealos
    - breeze
    - kubespray
    - linuxkit
    - kubeasz
- 部署 window 节点

### 插件扩展
- CNI
    - flannel
    - weave net
    - contiv
    - calico
    - ovn
    - sr-lov
    - romana
    - opencontrail
    - canal
    - kuryr-kubernetes
    - cilium
    - cni-genie
    - kube-router
    - nuage
    - multus-cni
    - virtlet
- CSI
    - ceph
- CRI
    - docker
    - hypercontainer
    - runc
        - cri-containerd
        - cri-o
    - gvisor
    - rkt
    - mirantis
    - infranetes
- Scheduler 扩展
    - sticky node scheduler
    - ksched
    - kube-node-index-prioritizing-scheduler
- Device 插件
- keepalived-vip
- external DNS
- kubevirt
### 服务治理
- service mesh
    - istio
    - linkerd
    - conduit
- helm
- CICD
    - gitlab-ci
    - jenkins
    - drone
    - apollo
    - skaffold
    - jenkins X
    - spinnaker
    - kubernetes pipeliner
    - draft 
    - forge
    - flux
    - gitkube
    - kubeci
    - keel
    - brigade
    - 灰度 shipper
- kompose

# Kubernetes 周边生态
## 客户端
- 桌面客户端
    - Lens `推荐`
    - Kubernetic
- 移动客户端
    - Cabin
    - Kubernav `推荐`

## Dashboard
- KubeSphere
- Kuboard
- K8Dash
- Octant
- fist
- konstellate
