# Deployment NGINX with Kubernets

This repository contains the kubernetes manifests required to deploy an NGINX application using a Deployment, expose it using a service and route traffic with an Ingress. 


### Prerequisites

* A running kubernetes cluster
* kubectl installed and configured
* An Ingress Controller (e.g NGINX Controller) installed in your cluster


### Deploying Instructions 

Follow the steps below to deploy NGINX on your kubernetes cluster : 

1. **Clone the Repo**
2. **Apply the Deployment**
   ```kubectl apply -f deployment.ym```
3. **Apply the Service**
   ```kubectl apply -f service.yml```
4. **Apply the Ingress**
   ```kubectl apply -f nginx-ingress.yml```


