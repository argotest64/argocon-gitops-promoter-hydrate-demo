
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 0d4e8e7970b5f3e2fb6bf0e5596e85abfd159903
kustomize build ./user-configuration/production/us-east-2
```