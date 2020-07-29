páginas:
https://github.com/kubernetes/dashboard
https://medium.com/kubernetes-costa-rica/kubernetes-nodeport-vs-loadbalancer-vs-ingress-cuando-usar-cu%C3%A1l-5930df5619c

Para probar local:
==================

kubectl apply -f .\deployment.yaml

kubectl apply -f .\service.yaml

kubectl proxy

http://localhost:8080/api/v1/namespaces/default/services/http:hello:8080/proxy/


kubectl.exe get pod

kubectl.exe get svc

kubectl.exe get all

Para borrar deploy:
===================

kubectl delete -f .\service.yaml

kubectl delete -f .\deployment.yaml