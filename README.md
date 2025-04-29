
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout b5fbe3f63d3cedacba8789e77dc80da84e7d938c
kustomize build ./user-configuration/development
```