## Requirements
```
kustomize
kubectl
kubectx (optional)
```

## Usage
Clone the repository change directory into it:
```
git clone https://github.com/ankitkumarakt746/k8s_sample_app.git
cd k8s_sample_app
```

Make sure your kubectl is configured to your minikube cluster and run:
```
kubectl apply -k .
```
