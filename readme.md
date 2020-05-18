

## Installation

```

git clone https://github.com/bhavinsa/nodejs-k8.git
cd nodejs-k8

```


#### Docket and Kubernetes commands


```bash

docker build . -t bhavinsa/nodejs-k8
docker push  bhavinsa/nodejs-k8
kubectl get nodes
kubectl create ns example-app
kubectl apply -n example-app -f .\deployment\deployment.yaml
kubectl -n example-app get deploy
kubectl -n example-app logs example-deploy-6f74b65b5b-j76d4 (ID)
kubectl apply -n example-app -f .\deployment\service.yaml
kubectl -n example-app get svc

```


#### Open the url - http://localhost/

