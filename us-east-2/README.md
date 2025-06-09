
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout d42547f63b0b691b732cd507501075263f49b29a
kustomize build ./user-configuration/production/us-east-2
```