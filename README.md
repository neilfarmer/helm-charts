# helm-charts

To install the `issuer` helm chart

```sh
helm repo add neilfarmer https://neilfarmer.github.io/helm-charts

helm install neilfarmer neilfarmer/issuers --set clusterIssuer=staging
```

To install the `fancy-todo` helm chart

```sh
helm repo add neilfarmer https://neilfarmer.github.io/helm-charts

helm install neilfarmer neilfarmer/fancy-todo
```
