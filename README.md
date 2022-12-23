kubectl label ns default environment=test
kubectl create deploy nginx --image=nginx --replicas=6
