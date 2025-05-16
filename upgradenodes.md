Upgrade Worker Node: 

1. vim /etc/apt/sources.list.d/kubernetes.list --> deb [signed-by=/etc/apt/keyrings/kubernetes-apt-keyring.gpg] https://pkgs.k8s.io/core:/stable:/v1.32/deb/ /
2. apt update 
   apt-cache madison kubeadm
3. apt-get install kubeadm=1.32.0-1.1
   kubeadm upgrade node
4. apt-get install kubelet=1.32.0-1.1
5. systemctl daemon-reload
   systemctl restart kubelet
