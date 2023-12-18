## GitOps 권한 (need to revisit)
```bash
oc adm policy add-cluster-role-to-user application-set-admin system:serviceaccount:openshift-gitops:openshift-gitops-argocd-server
```