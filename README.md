
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 05f113d2f50f88577c51bbb07945b14659a44b11
kustomize build ./user-configuration/development
```