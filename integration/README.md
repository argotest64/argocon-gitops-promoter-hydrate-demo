
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 215d87f25ad23d909281eafdd21c2dcfd1ee756c
kustomize build ./user-configuration/staging/integration
```