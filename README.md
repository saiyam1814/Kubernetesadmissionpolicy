
## Validating Admission Policy - Kubernetes 1.26 lpha feature examples repo


<img width="787" alt="Screenshot 2022-12-23 at 12 37 12 PM" src="https://user-images.githubusercontent.com/8190114/209288910-4bd7eaba-e826-4c6e-aa84-13df6a3030c3.png">




```
kubectl label ns default environment=test

kubectl create deploy nginx --image=nginx --replicas=6
```
