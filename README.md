# PyOnK8S
Simple Python app running on K8S

### Run:
1. 
kubectl apply –f https://raw.githubusercontent.com/Dgotlieb/PyOnK8S/master/flask-deploy.yaml

2.
kubectl apply –f https://raw.githubusercontent.com/Dgotlieb/PyOnK8S/master/flask_service.yaml

3. 
minikube service hello-python-service --url
