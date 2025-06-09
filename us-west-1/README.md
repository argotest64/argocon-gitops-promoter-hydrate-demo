
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout d784a19e76accd2b491e48af1f30117e94dc5b94
kustomize build ./user-configuration/production/us-west-1
```