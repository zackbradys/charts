# Rancher-Demo-App Helm Chart

| Type | Chart Version | App Version |
| ---- | ------------- | ----------- |
| application | `1.4.0` | `1.1.0` |

## Installing the Chart
```bash
helm install -n
```
```bash
helm status -n
```

## Uninstalling the Chart
```bash
helm uninstall -n
```

## Configuration

The following table lists the configurable parameters of the Rancher-demo-app chart and their default values.

| Parameter | Default | Description |
| --------- | ------- | ----------- |
| `replicaCount` | `6` |  |
| `image.repository` | `"zackbradys/rancher-demo-app"` |  |
| `image.tag` | `"1.1.0"` |  |
| `image.pullPolicy` | `"Always"` |  |
| `imagePullSecrets` | `[]` |  |
| `nameOverride` | `""` |  |
| `fullnameOverride` | `""` |  |
| `app.localization.title` | `"Rancher Federal Demo App"` |  |
| `app.localization.pets` | `"cows"` |  |
| `app.localization.color` | `"black"` |  |
| `service.type` | `"ClusterIP"` |  |
| `service.port` | `80` |  |
| `service.nodePort` | `""` |  |
| `ingress.enabled` | `false` |  |
| `ingress.annotations` | `{}` |  |
| `ingress.paths` | `[]` |  |
| `ingress.host` | `""` |  |
| `ingress.tls` | `[]` |  |
| `resources` | `{}` |  |
| `nodeSelector` | `{}` |  |
| `tolerations` | `[]` |  |
| `affinity` | `{}` |  |