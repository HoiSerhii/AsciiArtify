1. Install k3d 
```
wget -q -O - https://raw.githubusercontent.com/k3d-io/k3d/main/install.sh | bash
```

2. Setup Argo
```
k3d cluster create argo
```

Some commands for info
```
kubectl cluster-info
kubectl get all -A
```

3. Create namespace
```
kubectl create namespace argocd
```

4. Add manifest
```
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
```
Review controls and containers
```
kubectl get all -n argocd
kubectl get po -n argocd -w
```

5. Port forward
```
kubectl port-forward svc/argocd-server -n argocd 8080:443
```