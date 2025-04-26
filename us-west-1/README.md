
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 3b2be31eff8ec3095167d02783b54356325ec12a
kustomize build ./user-configuration/production/us-west-1
```