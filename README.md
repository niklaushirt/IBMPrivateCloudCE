# IBMPrivateCloudCE


### Install Kubernetes / MiniKube
```bash
kubectl run hello-minikube --image=gcr.io/google_containers/echoserver:1.4 --port=8080

kubectl expose deployment hello-minikube --type=NodePort
kubectl get pod

curl $(minikube service hello-minikube --url)
```
