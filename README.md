# kubecompose
Docker Compose file for running Kube on MacOS with Docker Toolbox (https://www.docker.com/products/docker-toolbox)

Thanks to Miroslav Prasil for the inspiration.
(https://kmh.prasil.info/posts/kubernetes-with-docker-compose/)

## Running
```
docker-compose -f kubernetes-docker.compose.yml up
```


## API Server
Binds to API Server to http://localhost:8080

## Kubectl

```
kubectl get all --kubeconfig=localhost.config
```

## Stopping
```
docker-compose -f kubernetes-docker.compose.yml down
```
