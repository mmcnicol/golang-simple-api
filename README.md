# golang-simple-api


$ docker build -t simple-api .

$ docker run --rm --name simple-api -it simple-api:latest /bin/bash

$ docker run -d -p 8080:8080 --rm --name simple-api simple-api




kubectl apply -f deployment.yml


kubectl apply -f service.yml



http://localhost:30000/


kubectl get nodes

kubectl get deployments

kubectl get services

kubectl get pods

kubectl logs simple-api-77dff45c94-wwcpw


kubectl delete svc simple-api

