# Deploy


## Initital
    helm repo add grebble https://grebblesa.github.io/helm-charts
    helm repo update

## Deploy main node
    helm install --namespace grebble-main-node --create-namespace main-node grebble/main-node

## Deploy agent node
    helm install --namespace grebble-agent --create-namespace agent grebble/agent
