
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 905d148211f0f2d06d56ada5b95346214d917c46
kustomize build ./user-configuration/development
```