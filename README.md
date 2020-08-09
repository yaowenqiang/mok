Develop and Operate Microservices on  Kuberentes

> minikube addons enable ingress 
> minikube addons enable heapster 
. 
> kubectl run -it --rm --image=busybox  my-test
> curl -v my-service.default.svc.cluster.local
> kubectl edit deployment my-deployment
> kubectl rollout undo deployment/my-deployment
