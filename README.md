# argocd-ocp4-example-com
## Deployment
```
git clone https://github.com/dgo19/argocd-ocp4-example-com.git
cd argocd-ocp4-example-com
oc apply -k argocd/
oc apply -f argocd/application-argocd.yaml
```
