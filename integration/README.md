
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 014b8a9e8423bf570ee6206a22455963bbbb7311
kustomize build ./user-configuration/staging/integration
```