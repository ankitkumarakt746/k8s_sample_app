## Requirements
```
kustomize
kubectl
kubectx (optional)
```

## Usage
Clone the repository change directory into it:
```
git clone repo
cd repo
```

Make sure your kubectl is configured to your minikube cluster and run:
```
kubectl apply -k .
```