
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout efb10e46237b1a7a063c6cc8dab397cf67a4ea92
kustomize build ./user-configuration/staging/e2e
```