# Deploy-MongoDB-and-Mongo-Express-Into-Minikube

## 1/kubectl apply commands in order : 

kubectl apply -f mongo-secret.yaml
kubectl apply -f mongo.yaml
kubectl apply -f mongo-configmap.yaml 
kubectl apply -f mongo-express.yaml
