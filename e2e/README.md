
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout aea6a9f0af45c6acb71a707bebbcace9090ca33f
kustomize build ./user-configuration/staging/e2e
```