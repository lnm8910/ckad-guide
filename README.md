# A guide to Certified Kubernetes Application Developer (CKAD)

## What is Kubernetes?
According to official documentation, Kubernetes, also known as K8s, is an open-source system for automating deployment, scaling, and management of containerized applications.

### Working with Pods using kubectl command

**Get all pods**
`kubectl get pods`

**Create New Pod**
`kubectl run [pod-name] --image=nginx:alpine`

**Forward Port**
`kubectl port-forward [pod-name] 8080:80`

**Delete pod**
`kubectl delete pod [pod-name]`


### Defining a Pod using YAML

`kubectl create -f [file-name] --save-config`

`kubectl describe pod [pod-name]`

`kubectl apply -f [file-name]`

`kubectl exec [pod-name] -it sh`

`kubectl edit -f [file-name]`

`kubectl delete -f [file-name]`
