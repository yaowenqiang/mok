Develop and Operate Microservices on  Kuberentes

> minikube addons enable ingress 
> minikube addons enable heapster 
. 
> kubectl run -it --rm --image=busybox  my-test
> curl -v my-service.default.svc.cluster.local
> kubectl edit deployment my-deployment
> kubectl rollout undo deployment/my-deployment
> kubectl get storageclass
> nslookup my-service

> kubectl create configmap my-configmap --from-file=./config
> kubectl create secret generic my-secret --from-file=./secret
> kubectl edit secrect my-secret
> kubectl create secret generic my-order-secrect --from-iteral=somevariable=somevalue
> https://docs.gitlab.com/charts/installation/
. https://docs.gitlab.com/ce/ci/docker/using_docker_build.html

> https://docs.gitlab.com/omnibus/docker/

