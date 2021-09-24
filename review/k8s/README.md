# CKAD

* Cluster commands
  kubectl get nodes
  kubectl cluster-info --context kind-ckad
  kubectl config get-clusters
  kubectl config use-context kind-ckad

* Common/utils commands
  kubectl apply -f review/k8s/1_pod/pod.yaml
  kubectl port-forward pod/nodejsserver 8080:8080
