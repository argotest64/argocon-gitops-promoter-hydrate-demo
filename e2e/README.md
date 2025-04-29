
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout e35c87f62855bc304d379653f36891eb84fd0e60
kustomize build ./user-configuration/staging/e2e
```