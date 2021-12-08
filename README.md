# myapp-k8s
treinando kubernetes


kubectl apply -f 01-ns.yaml --namespace=open5gs-k8s 
kubectl apply -f 02-service.yaml --namespace=open5gs-k8s 
kubectl apply -f 03-pod.yaml --namespace=open5gs-k8s 