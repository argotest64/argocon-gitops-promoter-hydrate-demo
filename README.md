
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout b73b9a6513121bdecae79849e721a788addbb8a8
kustomize build ./user-configuration/development
```