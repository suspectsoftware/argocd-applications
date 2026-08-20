# Argo CD Applications

Rendered Kubernetes manifests deployed by Argo CD.

Each top-level directory becomes an Argo CD Application and namespace. Pipelines
should render charts elsewhere and replace the manifests in the matching directory.
