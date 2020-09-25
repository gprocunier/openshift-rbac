oc describe rolebinding.rbac -n projectx89

oc describe role cicd-role

oc adm node-logs --role=master --path=kube-apiserver/ --as system:admin

oc adm policy who-can view pods

oc auth can-i view pods
