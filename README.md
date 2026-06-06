##project : local Kubernetes cluster with minikube



this repo contains the deployment config files and verification screenshots for setting up and scalling a local K8s cluster using minikube and docker.



##peoject files

* "deployment.yaml" : config and nginx deployment starting with 2 replicas.
* "service.yaml" : exposes the nginx deployment locally via port 30080.



##steps

1. started the local cluster using docker
2. applied config
3. verified initial pods and accessed the nginx welocome page using minikube
4. scaled the deployment to 5 replicas
5. verified the newly created pods using 'kubectl get pods'

