#Helm chart for ng-auth-ui

to update/publish:

Bump version of src/Chart.yaml

helm package src -d charts

helm repo index charts
