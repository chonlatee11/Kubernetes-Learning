# Kubernetes-Learning
 Learning Kubernetes and docker
## Kubectl commad
### ดูทรัพยากรทั้งหมด
    Kubectl get all
### ดู pods
    Kubectl get pods
### ใช้งานไฟล์ ต้องเป็นไฟล์นามสกุล .yml เท่านั้น
    Kubectl apply -f <file.yml>
### ดู services ทั้งหมด
    Kubectl get services
### ดูลอก pod
    Kubectl logs mypod
### ลบ pod
    Kubectl delete pod mypod
### ลบ service
    Kubectl delete pod/service --all
### ลบ service ทั้งหมด
    Kubectl delete all --all
![https://kubernetes.io/docs/reference/kubectl/cheatsheet/]