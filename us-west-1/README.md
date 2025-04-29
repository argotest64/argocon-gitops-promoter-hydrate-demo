
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 3b5497adcb2edc60bb1608ad6f61baa78e625fea
kustomize build ./user-configuration/production/us-west-1
```