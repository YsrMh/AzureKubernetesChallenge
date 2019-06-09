# AzureKubernetesChallenge

## Tasks
get aks version

`az aks get-versions --location westeurope`

create an AKS Cluster with SP

` az aks create --name <name must be unique> --resource-group akschallenge --location westeurope --enable-addons monitoring --kubernetes-version 1.13.5 --generate-ssh-keys --service-principal <app ID> --client-secret <secret>`

