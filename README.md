# gitops-repo-testing

To see things working:

git checkout dev
kustomize build services/service-a/dev
kustomize build apps/app-1/dev
kustomize build envs/dev

or kustomize apply -k these paths

git checkout staging
kustomize build services/service-a/staging
kustomize build apps/app-1/staging
kustomize build envs/staging

etc