
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout f86b010dcb826e91f3b9251eaf7be9ee1aed6bc6
kustomize build ./user-configuration/production/us-east-2
```