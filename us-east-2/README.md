
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 3f1cfc1b631404b04c2e8b7525123387b64d7a4e
kustomize build ./user-configuration/production/us-east-2
```