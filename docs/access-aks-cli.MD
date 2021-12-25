## Access Azure Kubernetes Cluster from Local Machine. 
## Install Azure CLI
```sh

## Downlaod & Install Azure CLI on Windows
https://aka.ms/installazurecliwindows
```

## Once download is complete, Install .msi file to get azure cli
```sh
Open CMD
type az --help --> to test whether Azure CLI is installed correctly or not
```
## Once Installation is completed, need to Access Azure with below commands
```sh
az login
az account set --subscription <SubscriptionName> --> Incase if we have multiple subscriptions
az aks get-credentials --resource-group=<RGNAME> --name=<AKSCLUSTERNAME>
```
## Install kubectl command line package in Local Windows Machine
```sh
curl -LO https://dl.k8s.io/release/v1.22.0/bin/windows/amd64/kubectl.exe
```

