~~~
kubectl  apply -f momo-git.yaml
watch kubectl -n flux-system get kustomizations.kustomize.toolkit.fluxcd.io flux-momo
watch kubectl -n flux-system get gitrepositories.source.toolkit.fluxcd.io momo
~~~
