# kubeflow-pipeline-gcp
## Changes added are for namespace and application name
```
vi pipelines/manifests/kustomize/cluster-scoped-resources/params.env 
vi pipelines/manifests/kustomize/base/params.env
kubectl apply -k pipelines/manifests/kustomize/cluster-scoped-resources
kubectl apply -k pipelines/manifests/kustomize/env/dev/
```
