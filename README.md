# kubernetes_projects
Projects using kubernetes

# Iniciar nodos
- minikube start --nodes 2 -p multinode-demo

# obtener info nodos y ips
- kebuctl get pods -o wide
## lanzar imagen 
- kubectl create deployment httpenv --image jpetazzo/httpenv
## scaled
- kubectl scale deployment httpenv --replicas=10
## ver todos los servicios
- kubectl get all
