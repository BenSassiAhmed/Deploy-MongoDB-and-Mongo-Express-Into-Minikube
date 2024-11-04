# Deploy-MongoDB-and-Mongo-Express-Into-Minikube

## 1/kubectl apply commands in order :  <br /> 

kubectl apply -f mongo-secret.yaml  <br /> 
kubectl apply -f mongo.yaml  <br /> 
kubectl apply -f mongo-configmap.yaml  <br /> 
kubectl apply -f mongo-express.yaml  <br /> 

## 2/ kubectl get commands

kubectl get pod <br /> 
kubectl get pod --watch <br /> 
kubectl get pod -o wide <br / > 
kubectl get service <br />  
kubectl get secret <br /> 
kubectl get all | grep mongodb  <br /> 
