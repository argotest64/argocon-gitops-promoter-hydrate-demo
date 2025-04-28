
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout e73eb13c089cee437e91440fa01d9fcea38e4404
kustomize build ./user-configuration/development
```