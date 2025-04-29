
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 3b156c2bd5cb4dc382d47d0390044092aa823006
kustomize build ./user-configuration/production/us-east-2
```