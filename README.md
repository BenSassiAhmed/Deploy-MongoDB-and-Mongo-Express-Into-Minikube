![image](https://github.com/user-attachments/assets/5350de50-950c-4d3a-bb30-4916e0378895)

![image](https://github.com/user-attachments/assets/9c2238d4-3cbd-42e9-8b97-600254dfddfc)


# Deploy-MongoDB-and-Mongo-Express-Into-Minikube

## 1/kubectl apply commands in order :  <br /> 

kubectl apply -f mongo-secret.yaml  <br /> 
kubectl apply -f mongo.yaml  <br /> 
kubectl apply -f mongo-configmap.yaml  <br /> 
kubectl apply -f mongo-express.yaml  <br /> 

## 2/ kubectl get commands

kubectl get pod <br /> 
kubectl get pod --watch  <br /> 
kubectl get pod -o wide  <br /> 
kubectl get service    <br /> 
kubectl get secret <br /> 
kubectl get all | grep mongodb   <br /> 

## 3/give a URL to external service in minikube <br /> 

minikube service mongo-express-service
