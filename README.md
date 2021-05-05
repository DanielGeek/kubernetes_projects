# kubernetes_projects
Projects using kubernetes

# Iniciar nodos
- minikube start --nodes 2 -p multinode-demo

# describe service
kubectl describe service name_service
# get nodos and ips
- kubectl get nodes -o wide

# obtener info nodos y ips
- kebuctl get pods -o wide
- kubectl get service
## lanzar imagen 
- kubectl create deployment httpenv --image jpetazzo/httpenv
## scaled
- kubectl scale deployment httpenv --replicas=10
## ver todos los servicios
- kubectl get all
