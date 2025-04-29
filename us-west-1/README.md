
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout c6dd7bacc809ad62fab16d179f2d00ce7978cf40
kustomize build ./user-configuration/production/us-west-1
```