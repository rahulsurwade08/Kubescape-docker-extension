# Kubescape-docker-extension

[Kubescape](https://github.com/kubescape/kubescape) is a K8s open-source tool providing a Kubernetes single pane of glass, including risk analysis, security compliance, RBAC visualizer, and image vulnerability scanning. Kubescape scans K8s clusters, YAML files, and HELM charts, detecting misconfigurations according to multiple frameworks (such as the NSA-CISA, MITRE ATT&CK®), software vulnerabilities, and RBAC (role-based-access-control) violations at early stages of the CI/CD pipeline, calculates risk score instantly and shows risk trends over time.

This is an open repository to migrate Kubescape into Docker Extensions.

This extension can help user to manage their K8s and Containers in following ways - 
- It will help to scans K8s clusters, YAML files, and HELM charts for detecting misconfigurations according to different frameworks like NSA,CISA, Mitre etc.
- Scan K8s manifest directly from github repository.
- Scan Kustomize Directly with a single command.
- Provide output of scanned results in different formats like JSON, junit xml, PDF, html, promethueus metrics.

----------------------------------------------------------------------------------------------------------------------------------------------------------
