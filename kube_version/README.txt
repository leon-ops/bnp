Prérequis : on suppose que le ingress controller est déjà installé

Comment lancer ?

kubectl apply -f frontend-deployment.yaml
kubectl apply -f backend-deployment.yaml
kubectl apply -f ingress.yaml