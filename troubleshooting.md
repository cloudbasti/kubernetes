CNI:
https://kubernetes.io/docs/tasks/administer-cluster/migrating-from-dockershim/troubleshooting-cni-plugin-related-errors/

kubectl: 
https://kubernetes.io/docs/tasks/debug/debug-cluster/troubleshoot-kubectl/

NODES:
kubectl debug node
https://kubernetes.io/docs/tasks/debug/debug-cluster/kubectl-node-debug/

crictl:
https://kubernetes.io/docs/tasks/debug/debug-cluster/crictl/


Network Policies: 
kubectl exec -it frontend -- curl -m 5 <BACKEND-POD-IP> (go into frontend pod and see if traffic works to backend pod)
