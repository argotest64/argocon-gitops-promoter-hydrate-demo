
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 08cf9f8383f3c5809d0ad0e9567b82c8bd7aa9e6
kustomize build ./user-configuration/development
```