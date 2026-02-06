# k8s
kubectl is only cli which resposbile for interacting with the k8s cluster via api server

1) kubectl --version
2) kubectl start
3) kubectl config current-context
4) kubectl describe pod <pod-name>
5) kubectl logs pod-name
6) kubectl events pod pod-name
7) adding  -watch f;ag can be helpful to stream updates in the terminal
8) kubectl confit set context minikube
9) kubectl run <pod-name> --image= <image-name> // example kubectl run nginx --image=nginx:1.27.0
10) kubectl get pods
11) kubectl describe <resource> <name> /// example kubectl describe pod nginx
12) kubectl delete <resource> <name> // example kubectl delete pod alpine
13) kubectl expose pod nginx --type=NodePort --port=80
14) kubectl get service
15) kubectl delte service nginx
16) 
