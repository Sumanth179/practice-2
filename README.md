# practice-2
-------
kubernets
go to powershell 
minikube start
kubectl create deployment mynginx --image=nginx
kubectl get deployments
kubectl expose deployment myngix --type=NodePort --port=80 --target-port=80
kubectl scale deployment mynginx --replicas=4
kubectl get deployments
kubectl get pods
kubectl port-forward svc/mynginx 8081:80
go to the browser and serarch localhost:8081
open another powershell and
minikube dashboard
go to the previous powershell and ctrl c
kubectl delete deployment mynginx
kubectl delete service mynginx
minikube stop
