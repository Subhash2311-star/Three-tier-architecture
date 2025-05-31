# Install EKS

Please follow the prerequisites doc before this.

## Create EKS cluster( it will take 10 to 15 min)

```
eksctl create cluster --name demo-cluster-three-tier-1 --region us-east-1
```

## Delete the cluster

```
eksctl delete cluster --name demo-cluster-three-tier-1 --region us-east-1
```



