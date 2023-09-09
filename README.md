#Deploy ArgoCD, cluster-wide subscriptions and create namespaces

```shell
oc apply -f gitops/sub.yaml
oc apply -f gitops/ns.yaml
oc apply -f gitops/idp.yaml
```

```shell
oc apply -f ./argocd/project.yaml
```

```shell
oc apply -f ./argocd/application.yaml
```


