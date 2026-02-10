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
15) kubectl delete service nginx
16) kubectl create -f nginx-pod.yaml // run pod using  manifest file for imperative command kubectl run <pod-name> --image= <image-name> // example kubectl run nginx --image=nginx:1.27.0
17) kubectl create -f nginx-svc.yaml // create manifest file for imperative command kubectl expose pod nginx --type=NodePort --port=8
18) kubectl run nginx --image=nginx:1.27.0 --dry-run=client -o yaml  //export yaml file for impertative command
19) kubectl expose pod nginx-pod --type=NodePort --port=80 --dry-run=client -o yaml //export yaml file for imperative command
20) kubectl create -f file-name.yaml
21) kubectl delete -f file-name.yaml
22) kubectl apply -f file-name.yaml
23) kubectl replace -f file-name.yaml
24) kubectl get deploy
25) kubectl get rs
26) kubectlt describe rs replica-set-name
27) kubectl describe deploy deployment-name
28) 
