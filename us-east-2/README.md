
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 0f4d76eab8487b34cceddea977709ed76581c422
kustomize build ./user-configuration/production/us-east-2
```