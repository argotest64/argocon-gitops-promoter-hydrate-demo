
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 06ee1390f7d51667a2ea79a9b49726b63c139d84
kustomize build ./user-configuration/production/us-west-1
```