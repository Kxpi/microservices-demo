# 1 - February 8th

![image](https://user-images.githubusercontent.com/70852683/219963846-873b0837-e37d-4f83-a4a6-586f5c1f0266.png)

a) Install minikube, setting up minikube
* Already installed
* Steps to create cluster (1-node):
  * ``` minkube start ```

b) Deploy sock-shop platform(based on micro-services) in kubernetes with a demo app ready using this [folder](/deploy/kubernetes/manifests)
* In repo top-level dir: ```kubectl apply -f deploy/kubernetes/manifests```
* In another terminal : ```minikube service front-end -n sock-shop --url```
* Using URL that pops up without closing this terminal allows for access via NodePort
* [More on accessing](https://minikube.sigs.k8s.io/docs/handbook/accessing/)
* Delete using ```kubectl delete -f deploy/kubernetes/manifests```

c) Setting up helm v3
* Already had it too (**get-helm.sh** script)

d) Deploy simple application using helm 
* https://github.com/Kxpi/flask-ip-app 


# 2 - February 20th
