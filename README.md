# gitops-repo-testing

To see things working:

```sh
git checkout dev
kustomize build services/service-a/overlays
kustomize build apps/app-1/overlays
kustomize build env/overlays
```

or `kustomize apply -k` these paths


