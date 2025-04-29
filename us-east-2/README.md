
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 2ee47d0957743cb8ccf790d87a47084de0df8e59
kustomize build ./user-configuration/production/us-east-2
```