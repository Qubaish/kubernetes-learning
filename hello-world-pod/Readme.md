// Create Pod
kubectl create -f helloworld.yaml 

// deployed pod

kubectl expose deployment helloworld --type=NodePort

// Run Service through minikube

minikube service helloworld