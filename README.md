# Aliyun docker register

## Now include

+ Kubernetes v1.15.1 (amd64)
  + kube-proxy
  + kube-apiserver
  + kube-scheduler
  + kube-controller-manager
  + etcd
  + coredns
  + metrics-server
  + pause
  + defaultbackend
+ Tensorflow
  + tensorflow-1.13.1-gpu-py3

## Usage:

+ kubernetes:

  ```
  docker pull registry.cn-hangzhou.aliyuncs.com/innohub/<k8s-image-name>:<tag>
  ```

+ tensorflow

  ```
  docker pull registry.cn-hangzhou.aliyuncs.com/innotensor/tensorflow:1.13.1-gpu-py3
  ```

  