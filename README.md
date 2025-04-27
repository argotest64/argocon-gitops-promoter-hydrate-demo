
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout b622a9de3173753cd1026e8260238a33074a6df5
kustomize build ./user-configuration/development
```