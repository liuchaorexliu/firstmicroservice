# firstmicroservice
first dotnet core microservice 

tutoria: https://dotnet.microsoft.com/learn/aspnet/microservice-tutorial/install-docker

docker image:
docker tag firstmicroservice liuchaorexliu/firstmicroservice
docker push liuchaorexliu/firstmicroservice



k8s deploy: 
cd DeployFile 
kubectl apploy -f webapp_namespace.yaml
kubectl apploy -f webapp_deploy.yaml
kubectl apploy -f webapp_service.yaml
