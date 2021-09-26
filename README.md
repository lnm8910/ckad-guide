# A guide to Certified Kubernetes Application Developer (CKAD)

## What is Kubernetes?
According to official documentation, Kubernetes, also known as K8s, is an open-source system for automating deployment, scaling, and management of containerized applications.

##### Get all pods
`kubectl get pods`

##### Create New Pod
`kubectl run my-nginx --image=nginx:alpine`

##### Forward Port
`kubectl port-forward my-nginx 8080:80`

##### Delete pod
`kubectl delete pod my-nginx`

