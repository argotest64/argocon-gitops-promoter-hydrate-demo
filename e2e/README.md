
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout a21df399979c1e6415b5017cca9f5c462e32ec36
kustomize build ./user-configuration/staging/e2e
```