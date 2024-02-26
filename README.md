 kubernetes_assessment26
Deploying python application in kubernetes
Wrote docker file for python application
Built and push the docker image
Deploy and manage the lifecycle of a containerized application on Kubernetes using minikube, kubectl
We the get enpoint of html  file.
Commands used for deploying and running:
cd 26feb
docker build -t maitreyeemitra/assessment26:latest .
docker run -it  maitreyeemitra/ assessment26:latest
docker push  maitreyeemitra/ assessment26:latest
minikube status
kubectl apply -f manifest.yaml
kubectl apply -f service.yaml
 kubectl get pods
docker context use deployment
minikube start --driver=docker
minikube assessment quotes-service




