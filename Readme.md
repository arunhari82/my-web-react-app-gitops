# Install Openshift-gitops Operator
``` 
    oc new-project react-app-demo
    oc label namespace react-app-demo argocd.argoproj.io/managed-by=openshift-gitops
    oc apply -f ./argocd
```    