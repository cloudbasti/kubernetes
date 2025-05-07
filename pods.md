kubectl run --restart=Never --image=busybox static-busybox --dry-run=client -o yaml --command -- sleep 1000 > /etc/kubernetes/manifests/static-busybox.yaml

/var/lib/kubelet/config.yaml #path for static pods

Admission Controllers:
ps -ef | grep kube-apiserver | grep admission-plugins  
