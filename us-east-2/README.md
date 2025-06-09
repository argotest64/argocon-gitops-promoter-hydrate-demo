
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout c3ef1fbcd78740e18597bae84a97740a5de14621
kustomize build ./user-configuration/production/us-east-2
```