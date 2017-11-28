# kubecompose
Docker Compose file for running Kube in Compose on OS/X with Docker Toolbox (https://www.docker.com/products/docker-toolbox
)

## Running
```
docker-compose -f kubernetes-docker.compose.yml up
```

## Kubectl

```
kubectl get all --kubeconfig=localhost.config
```

## Stopping
```
docker-compose -f kubernetes-docker.compose.yml down
```
