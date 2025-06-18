```
kubectl apply -f mongo-configmap.yaml
kubectl apply -f mongodb-secret.yaml
kubectl apply -f mongodb-deployment.yaml
kubectl apply -f mongodb-service.yaml
kubectl apply -f mongo-express-deployment.yaml
```

start mongodb express service
```
minikube service mongo-express-service
```
