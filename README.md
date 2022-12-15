### Cluster Architecture

- https://kubernetes.io/docs/concepts/architecture/

### Pods

- https://kubernetes.io/docs/concepts/workloads/pods/

### Deployment

- https://kubernetes.io/docs/concepts/workloads/controllers/deployment/

### Service

- https://kubernetes.io/docs/concepts/services-networking/service/

### ReplicaSet

- https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/

### ConfigMaps

- https://kubernetes.io/docs/concepts/configuration/configmap/

### Secrets

- https://kubernetes.io/docs/concepts/configuration/secret/

### minikube and kubectl

- https://minikube.sigs.k8s.io/docs/

- Getting started - https://minikube.sigs.k8s.io/docs/start/

### Ingress and Ingress Controller

- Ingress - https://kubernetes.io/docs/concepts/services-networking/ingress/

- Working with NGINX Ingress - https://kubernetes.io/docs/tasks/access-application-cluster/ingress-minikube/

- Bare-metal considerations https://kubernetes.github.io/ingress-nginx/deploy/baremetal/

- _bulb_ Add the following line to the bottom of the vi /etc/hosts file on your computer (you will need administrator access, run with sudo):

  minikube ip hello-world.com

- Some notes,
  - pathType (Exact, Prefix, etc?) matters
  - Ingress also has something called default backend, for which you can create service and pod to show when it was redirected todefault backend - https://youtu.be/X48VuDVv0do?t=8368
  - Screenshot 2022-12-13 at 3.58.45 PM.png

### Namespaces

- https://kubernetes.io/docs/concepts/overview/working-with-objects/namespaces/

- https://kubernetes.io/docs/tasks/administer-cluster/namespaces-walkthrough/
