# Bitnami Postgresql Kubernetes

## Prerequisite
This deployment assumes that an instance of minikube cluster is available with a minimum hardware requirements

## Add bitnami chart to the helm
helm repo add bitnami  https://charts.bitnami.com/bitnami

## Install bitnami/postgresql chart
`helm install postgresql bitnami/postgresql -n bitnami -f .\postgresql-values.yaml`

## Uninstall bitnami/postgresql chart
`helm uninstall postgresql -n bitnami`
