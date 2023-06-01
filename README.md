## Installing Tekton in Kubernetes

### Purpose

### Tekton Pipelines

```
kubectl apply --filename https://storage.googleapis.com/tekton-releases/pipeline/latest/release.yaml
```

### Tekton Triggers

```
kubectl apply --filename \
https://storage.googleapis.com/tekton-releases/triggers/latest/release.yaml
kubectl apply --filename \
https://storage.googleapis.com/tekton-releases/triggers/latest/interceptors.yaml
```

### Tekton Dashboard

```
kubectl apply --filename https://storage.googleapis.com/tekton-releases/dashboard/latest/release.yaml
```

### Chains

```
kubectl apply --filename https://storage.googleapis.com/tekton-releases/chains/latest/release.yaml
```

### MiniKube

### Kind

### OpenShift

### K3d

### Links
