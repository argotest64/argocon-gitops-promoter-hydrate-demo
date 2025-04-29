
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 1a2690193edb0922e96ae6f724bc85225de7063e
kustomize build ./user-configuration/staging/integration
```