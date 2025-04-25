
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 8bdd03202c6dfcd2d17b126d128285b9ab652c6f
kustomize build ./user-configuration/staging/integration
```