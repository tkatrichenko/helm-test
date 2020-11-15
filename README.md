# helm-test

Access to helm repo
```
helm repo add my_github https://raw.githubusercontent.com/tkatrichenko/helm-test/master/helm/
helm repo update
helm search repo my_github
NAME                          	CHART VERSION	APP VERSION	DESCRIPTION
my_github/kube-kyc-dataset-app	1.0.0        	1.0.0      	A Helm chart for kube-kyc-dataset-app
```
