Playbook create-cluster.yml is used for Kubernetes cluster deployment on Ubuntu 

hosts file example:

[masters]  
k8s-master-1 ansible_host=192.168.40.125  
k8s-master-2 ansible_host=192.168.40.126  
k8s-master-3 ansible_host=192.168.40.127  
[workers]  
k8s-worker-1 ansible_host=192.168.40.128  
k8s-worker-2 ansible_host=192.168.40.129  
k8s-worker-3 ansible_host=192.168.40.130  
[all:vars]  
api_address=192.168.40.131 
kubernetes_version=v1.27.1 
