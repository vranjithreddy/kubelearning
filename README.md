# KubeLearning
Learn kubernetes with an sample application connecting front end with redis. 

This would build a multi-tier web application.

This application would have a front end connected to redis master for writes and redis slaves for reads. 


Use the following commands to create your cluster. 

kubectl apply -f redis-master-deployment.yaml
kubectl apply -f redis-master-service.yaml
kubectl apply -f redis-slave-deployment.yaml
kubectl apply -f redis-slave-service.yaml
kubectl apply -f frontend-deployment.yaml
kubectl apply -f frontend-service.yaml
