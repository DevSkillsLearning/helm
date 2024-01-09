## Helm Commands used in the course

|     Helm Command       |     Description          |
| ------------- | ------------- |
| "helm create [NAME]" | Create a default chart with the given name |
| "helm dependencies build" | To recompile the given helm chart |
| "helm install [NAME] [CHART]" | Install the given helm chart into K8s cluster |
| "helm upgrade [NAME] [CHART]" | Upgrades a specified release to a new version of a chart |
| "helm history [NAME]" | Display historical revisions for a given release |
| "helm rollback [NAME] [REVISION]" | Roll back a release to a previous revision |
| "helm uninstall [NAME]" | Uninstall all of the resources associated with a given release |
| "helm template [NAME] [CHART]" | Render chart templates locally along with the values |
| "helm list" | Lists all of the helm releases inside a K8s cluster |
