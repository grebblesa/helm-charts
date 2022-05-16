# Deploy


## Initital
    helm repo add grebble https://grebblesa.github.io/helm-charts
    helm repo update

## Deploy main node
    helm install --namespace grebble-main-node --create-namespace grebble-main-node main-node grebble/main-node
    helm install agent grebble/agent
