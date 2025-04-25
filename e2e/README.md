
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 95ca241dedb8d9841f4d13dfea6d2795ce7a736a
kustomize build ./user-configuration/staging/e2e
```